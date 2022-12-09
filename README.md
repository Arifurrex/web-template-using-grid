# web-template-using-grid


```css
.header {

    grid-area: hd;

}

.footer {

    grid-area: ft;

}

.content {

    grid-area: main;

}

.sidebar {

    grid-area: sd;

}
    
    ```
    
    
    ```css
    wrapper {

    display: grid;

    grid-template-columns: repeat(9, 1fr);

    grid-auto-rows: minmax(100px, auto);

    grid-template-areas:

      "hd hd hd hd   hd   hd   hd   hd   hd"

      "sd sd sd main main main main main main"

      "ft ft ft ft   ft   ft   ft   ft   ft";

}
    ```
    
    
    ```
    
    <div class="wrapper">

    <div class="header">Header</div>

    <div class="sidebar">Sidebar</div>

    <div class="content">Content</div>

    <div class="footer">Footer</div>

</div>
    ```html
   
    
    
    
    
