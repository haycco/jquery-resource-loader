jQuery Resource Loader Plugin
=============================
This jquery plugin can help you load resources (js/css) when visit web page in any time.

Installation
-------
    <script type="text/javascript" charset="utf-8" src="jquery.js"></script>
    <script type="text/javascript" charset="utf-8" src="jquery.resource.loader.min.js"></script>

Usage
-----

    $.ResourceLoader(
        ['css.css','test.js'], //what it is need to load
        { onlyOnce : true} //true : only included one time, false : it will be load when the page load or refresh.
    );


Testing
-------

To run the tests:

    $ rake

To add tests see the `Commands` section earlier in this
README.
