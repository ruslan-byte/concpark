<template>
    <div class="search">
        <form>
            <input type="text" placeholder="Быстрый поиск">
            <button type="submit"> 
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M11 19C15.4183 19 19 15.4183 19 11C19 6.58172 15.4183 3 11 3C6.58172 3 3 6.58172 3 11C3 15.4183 6.58172 19 11 19Z" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M21.0004 21L16.6504 16.65" stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
</svg>
            </button>
        </form>


    </div>
</template>
<style>

@import url('https://fonts.googleapis.com/css?family=Open+Sans');

.opensans {
  font-family: "Open Sans", sans-serif;
}
    .search input {
        padding-left: 17px;
        margin: 0;
        width: 356px;
        height: 48px;
        font-family: Open Sans;
        font-weight: 400;
        font-size: 14px;
        line-height: 14px;
        letter-spacing: 5%;
        border: 1px rgba(212, 212, 212, 1) solid; 
        border-top-left-radius: 3px;
        border-bottom-left-radius: 3px;
    }

    .search button {
        margin: 0;
        width: 56px;
        height: 51px;
        background: red;
        border-top-right-radius: 3px;
        border-bottom-right-radius: 3px; 
        border: 1px red solid;
        cursor: pointer;
        
    }

    form {
        position: relative;
        margin: auto;
    }
</style>