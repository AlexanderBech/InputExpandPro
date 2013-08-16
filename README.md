Auto-expand
===========

Jquery plugin wich provides the auto expanding in width and height of inputs and textarea's.

How-to:

* $('form input, form textarea').autoExpand();
* $('form input').autoExpand();
* $('input').autoExpand();
* $('#id_of_input_or_textarea').autoExpand();
* $('input').autoExpand({ width: 20, height: 20 });

Defaults:

	var defaults = {
		width : 20 , 	// the default width to add in as extra offset
		height : 20		// the default height(for textareas) to add in as extra offset
	};
