JSTL Snippits
=======================

### c:out

*Tab Trigger:* c-out

*Snippet File:* `c-out.sublime-snippet`

*Generates:*

    <c:out value="\$\{$1\}" />


### c:set

*Tab Trigger:* c-set

*Snippet File:* `c-set.sublime-snippet`

*Generates:*

    <c:set var="$1" value="\$\{$2\}" />


### c:choose

*Tab Trigger:* c-choose

*Snippet File:* `c-choose.sublime-snippet`

*Generates:*

    <c:choose>
        <c:when test="$1">
            $2
        </c:when>
        <c:otherwise>
            $3
        </c:otherwise>
    </c:choose>


### c:when

*Tab Trigger:* c-when

*Snippet File:* `c-when.sublime-snippet`

*Generates:*

    <c:when test="$1">
        $2
    </c:when>


### c:otherwise

*Tab Trigger:* c-otherwise

*Snippet File:* `c-otherwise.sublime-snippet`

*Generates:*

    <c:otherwise>
        $1
    </c:otherwise>


### c:if

*Tab Trigger:* c-if

*Snippet File:* `c-if.sublime-snippet`

*Generates:*

    <c:if test="$1">
        $2
    </c:if>


### c:for

*Tab Trigger:* c-for

*Snippet File:* `c-for.sublime-snippet`

*Generates:*

    <c:forEach var="$1" items="\$\{$2\}">
        $3
    </c:forEach>


### c:forEach

*Tab Trigger:* c-foreach

*Snippet File:* `c-foreach.sublime-snippet`

*Generates:*

    <c:forEach var="$1" items="\$\{$2\}" varStatus="${3:status}" step="$4" begin="$5">
        $6
    </c:forEach>
