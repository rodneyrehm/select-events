# <select> Events across browser

We already know that individual browsers handle `<input>` elements quite differently in terms of styling. This post details the results of testing the events triggered for simply selecting an option from a `select` element. WebKit does not equal WebKit and IE 10 is not IE 9 - go figure!

Today I investigated the flow of events for the simple task of *selecting an element from a drop-down menu (`<select>`)*, because someone reported an <a href="https://github.com/medialize/jQuery-contextMenu/issues/114">Issue with Select input command on Firefox</a>. The contextMenu can handle sub menus and form elements. The problem arises when a `<select>` is placed within a sub menu, but everything seems to work fine if the `<select>` is a root element. So what's going on here?




* FUCK… Need to re-test and test events of <option> as well
* test stuff with keys for bassistance





