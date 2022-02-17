# css_basics
=> You can select an element by
    type
    id
    class
    attribute
=> Attribute selector
    a[target="_blank"] {

    }
    a[href="https://google.com"]{
        
    }
    a[href*="google"]{

    }
    a[href^="https"]{

    }
    <!-- it will select all the anchor elements whose href will starts with https and ends with .com -->
    a[href^="https"][href$=".com"]{

    }