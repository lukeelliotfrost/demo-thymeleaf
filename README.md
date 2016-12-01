# demo-thymeleaf

The layout features are demonstrated in the following way:

The layout.html file wil include two Thymeleaf fragments under fragments folder, including header.html, footer.html.

The index.html file will use layout.html file as a template to create a complete html page (a complete Thymeleaf view).

The hello.html file will include alert.html fragment to show alerts on the page.


Structure of templates directory:

templates

    ├── fragments   
    │   ├── alert.html
    │   ├── footer.html  
    │   └── header.html    
    ├── hello.html    
    ├── index.html    
    └── layouts   
        └── layout.html
