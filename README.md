I changed the part where the library imports the query-ui to search for "jquery-ui" instead of "jquery-ui/ui/widgets/sortable", "jquery-ui/ui/widgets/draggable" and "jquery-ui/ui/widgets/droppable". This is to only have one file with the three libraries (This avoids errors).
