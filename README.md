# Superglue
A pure JavaScript client-side databinding library for HTML without dependencies. Facilitates HTML templates.

Like the well-kown cyano-acrylate glue, it should be possible to bind HTML elements to a data source in seconds. Bi-directional, declarative, with just HTML attributes. The concept is easy to grasp within minutes, even for beginners. Data sources should be created easily from JSON resources. They will be wrapped with a JavaScript Proxy to detect changes and update the bound HTML elements. Event handlers monitor changes to HTML elements and update the data source.

Bindable elements are text and attribute nodes -- that should cover almost every requirement.

Supported is property binding for simple objects, and list binding for arrays and array-like objects.

Integration of database backends is planned and will be implemented after the core binding functionality is done. Not sure whether that should be integrated into this project, maybe it is better to rely on external and well-known packages. However, write-access to a data source property shall create a copy of the original value, so it should be easy to detect changed or inserted data, and generate SQL insert and update statements, or call the related stored procedures, or make a REST request.

Contributors welcome.

Best wishes, and stay healthy!

