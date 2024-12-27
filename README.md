# Uncommon HTML Error: innerHTML with Non-String Value

This repository demonstrates an uncommon error in HTML that occurs when attempting to set the `innerHTML` property of an element with a non-string value.  The example shows that using a number (like 123) will not update the content as expected.

The solution provides a corrected version where the value is explicitly converted to a string before setting `innerHTML`.