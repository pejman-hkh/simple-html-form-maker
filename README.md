# simple-html-form-maker
Simple html form maker

Usage : 

```html
form = $("#form").formMaker()
.input( "test", "test", { "class" : "test" } )
.textarea( "test1", "test1", { "class" : "test" } )
.radio( "test2", "test2", [ "test", "test2" ], { "class" : "test"} )
.checkbox( "test2", "test2[]", [ "test", "test2" ], { "class" : "test"} )
.select( "test2", "test2[]", [ "test", "test2" ], { "class" : "test"} )
.file( "test", "test", { "class" : "test" } )
.end();

```
