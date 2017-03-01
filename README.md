# simple-html-form-maker
Simple html form maker

Usage : 

```html
form = $("#form").formMaker()
.startFormGroup( 2 )
.input( "test", "test", { class : "test" } )
.input( "test1", "test2", { class : "test" } )
.endtFormGroup( true )

.textarea( "test1", "test1", { class : "test" } )
.radio( "test2", "test2", [ "test", "test2" ], { class : "test"} )
.checkbox( "test2", "test2[]", [ "test", "test2" ], { class : "test"} )
.startFormGroup( 2 )
.select( "test2", "test2[]", [ "test", "test2" ], { class : "test"} )
.select( "test2", "test2[]", [ "test", "test2" ], { class : "test"} )
.endtFormGroup( true )

.file( "test", "test", { class : "test" } )
.end();
```
