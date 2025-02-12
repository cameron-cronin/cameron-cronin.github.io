<template>
    <div class="info">
            <div>
                <a class='number' href="mailto:cbcronin15@gmail.com">
                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px"  width="25" height="25"  viewBox="0 0 50 50">
                        <path d="M 5.5 7 C 3.019531 7 1 9.019531 1 11.5 L 1 11.925781 L 25 29 L 49 11.925781 L 49 11.5 C 49 9.019531 46.980469 7 44.5 7 Z M 6.351563 9 L 43.644531 9 L 25 22 Z M 1 14.027344 L 1 38.5 C 1 40.980469 3.019531 43 5.5 43 L 44.5 43 C 46.980469 43 49 40.980469 49 38.5 L 49 14.027344 L 43 18.296875 L 43 41 L 7 41 L 7 18.296875 Z"></path>
                    </svg>
                </a>
            </div>
            <div>
                  <!-- instagram -->
            <a class="link" target="_blank" href="https://www.instagram.com/cammyb15">
                <svg viewBox="0 0 24 24"    height="24px" width="24px"  fill="none" xmlns="http://www.w3.org/2000/svg"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <path fill-rule="evenodd" clip-rule="evenodd" d="M12 18C15.3137 18 18 15.3137 18 12C18 8.68629 15.3137 6 12 6C8.68629 6 6 8.68629 6 12C6 15.3137 8.68629 18 12 18ZM12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z" fill="#848484"></path> <path d="M18 5C17.4477 5 17 5.44772 17 6C17 6.55228 17.4477 7 18 7C18.5523 7 19 6.55228 19 6C19 5.44772 18.5523 5 18 5Z" fill="#848484"></path> <path fill-rule="evenodd" clip-rule="evenodd" d="M1.65396 4.27606C1 5.55953 1 7.23969 1 10.6V13.4C1 16.7603 1 18.4405 1.65396 19.7239C2.2292 20.8529 3.14708 21.7708 4.27606 22.346C5.55953 23 7.23969 23 10.6 23H13.4C16.7603 23 18.4405 23 19.7239 22.346C20.8529 21.7708 21.7708 20.8529 22.346 19.7239C23 18.4405 23 16.7603 23 13.4V10.6C23 7.23969 23 5.55953 22.346 4.27606C21.7708 3.14708 20.8529 2.2292 19.7239 1.65396C18.4405 1 16.7603 1 13.4 1H10.6C7.23969 1 5.55953 1 4.27606 1.65396C3.14708 2.2292 2.2292 3.14708 1.65396 4.27606ZM13.4 3H10.6C8.88684 3 7.72225 3.00156 6.82208 3.0751C5.94524 3.14674 5.49684 3.27659 5.18404 3.43597C4.43139 3.81947 3.81947 4.43139 3.43597 5.18404C3.27659 5.49684 3.14674 5.94524 3.0751 6.82208C3.00156 7.72225 3 8.88684 3 10.6V13.4C3 15.1132 3.00156 16.2777 3.0751 17.1779C3.14674 18.0548 3.27659 18.5032 3.43597 18.816C3.81947 19.5686 4.43139 20.1805 5.18404 20.564C5.49684 20.7234 5.94524 20.8533 6.82208 20.9249C7.72225 20.9984 8.88684 21 10.6 21H13.4C15.1132 21 16.2777 20.9984 17.1779 20.9249C18.0548 20.8533 18.5032 20.7234 18.816 20.564C19.5686 20.1805 20.1805 19.5686 20.564 18.816C20.7234 18.5032 20.8533 18.0548 20.9249 17.1779C20.9984 16.2777 21 15.1132 21 13.4V10.6C21 8.88684 20.9984 7.72225 20.9249 6.82208C20.8533 5.94524 20.7234 5.49684 20.564 5.18404C20.1805 4.43139 19.5686 3.81947 18.816 3.43597C18.5032 3.27659 18.0548 3.14674 17.1779 3.0751C16.2777 3.00156 15.1132 3 13.4 3Z" fill="#848484"></path> </g></svg>
            </a>
            </div>
    </div>
    <br>
    <div class="blur-container">
        <div class="blurred-background"></div>
        <img class="cover-img" src="/contact/image.jpg" />
    </div>
</template>
<script>
export default{
    title: "Contact"
}
</script>

<style scoped>
.blur-container{
    position: relative;
    display: grid;
    width: 100%;
    height: 1000px;
    margin-bottom: 80px;
    justify-items: center;
}
.blurred-background{
    width: 99%;
    height:80%;
    background-image: url('/contact/image.jpg');
    background-repeat: no-repeat;
    background-size: cover; 
    background-position:  center;
    filter: blur(8px);
    -webkit-filter: blur(8px);
}
.cover-img{
    height: 60%;
    position: absolute;
    top: calc((100% / 10));
    padding-left : auto;
    padding-right: auto;
    background: blue;
}
.info{
    /* margin-left: calc(100vw/4); */
    width:100%;
    display: grid;
    grid-template-columns: auto auto;
    justify-items: center;
    align-items: center;
    justify-content: center;
    grid-gap: 50px;
    background-color: rgb(245, 245, 245);
    opacity: .65;
    box-shadow:  0px 0px 16px 16px rgba(245, 245, 245);
    font-size: 25px;
    font-family: lato, sans-serif;
    font-weight: 400;
    overflow: hidden;
}
@media screen and (max-width: 800px) {
    .blur-container{
        width:90%;
        object-fit: cover;
        height: 65vw;
        margin-left: auto;
        margin-right: auto;
        margin-bottom: 20px;
    }
}
.number{
    text-decoration: none;
    color: black;
    font-family: lato, sans-serif;
    overflow: hidden;
    letter-spacing: .03rem;
}
</style>