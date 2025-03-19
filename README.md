# Belajar bikin login page dengan html, css
## Struktur Web
    page
        container
            h3 Login
            form
                box
                    p Username
                    input text
                box
                    p Password
                    input password
                box
                    box
                        p Remember Me
                        input checkbox
                    box
                        p Doesn't have account?
                        a Create Account
                button submit login

## Font
### Poppins (dari google font,  taruh di header) 
    <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
    </style>

## Cara Penggunaan Dasar
        .poppins-regular {
    font-family: "Poppins", sans-serif;
    font-weight: 400;
    font-style: normal;
    }

## Color
    :root {
    --Background: rgb(246, 248, 213);
    --Primary: rgb(33, 133, 213);
    --Secondary: rgb(52, 140, 212);
    --Text: Black;
    }