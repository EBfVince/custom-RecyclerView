# Demo project to test a custom `RecyclerView` with `tools:listitem`

### Initial setup
This is a blank project generated by *Android Studio 3.3 Beta 3*.

A `RecyclerView` has been added to `activity_main.xml` using `tools:listitem`
to get a preview of the list-items.

As expected, the layout-editor shows a list of items in the list.

![RecyclerView](img/layout-editor_RecyclerView.JPG)

### Custom View
To test a custom view which extends `RecyclerView`, `TestRecyclerView`
has been added and the layout has been altered to use this instead.

After building the project, the layout-editor only shows a white space
instead of the list-items.

![TestRecyclerView](img/layout-editor_TestRecyclerView.JPG)
