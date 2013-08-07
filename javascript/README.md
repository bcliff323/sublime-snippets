JavaScript Snippits
===================

### Module (Self-Executing Anonymous Function)

*Tab Trigger:* js-module

*Snippet File:* `js-module.sublime-snippet`

*Generates:*

    (function($2){
        $3
    })($1);


### Anonymous Function

*Tab Trigger:* js-anon-func

*Snippet File:* `js-anon-func.sublime-snippet`

*Generates:*

    function ($1) {
        $2
    };


### Named Function

*Tab Trigger:* js-func

*Snippet File:* `js-func.sublime-snippet`

*Generates:*

    function $1($2) {
        $3
    };


### If Statement

*Tab Trigger:* js-if

*Snippet File:* `js-if.sublime-snippet`

*Generates:*

    if($1) {
        $2
    }


### If, Else Statement

*Tab Trigger:* js-if-else

*Snippet File:* `js-if-else.sublime-snippet`

*Generates:*

    if($1) {
        $2
    } else {
        $3
    }


### For Loop

*Tab Trigger:* js-for

*Snippet File:* `js-for.sublime-snippet`

*Generates:*

    for(var = i, len = $1; i < len; i++) {
        $2
    }


### jsDoc Comment

*Tab Trigger:* js-doc

*Snippet File:* `js-doc.sublime-snippet`

*Generates:*

    /**
     * $1
     */


### jQuery Google CDN Script

*Tab Trigger:* jq-google

*Snippet File:* `jq-google.sublime-snippet`

*Generates:*

    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"></script>
