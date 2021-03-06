=========
reST test
=========

.. |D2014| image:: res/Doc2014_11pt.png
.. |Infor| image:: res/Info_11pt.png

.. centered:: TEST TRACE FLAGS

.. rubric:: Test Trace Flags




2388 ``Doc2005`` *Info*
	920093_: does the blah blah to the blah blah and sometimes also the blah blah. This is a really long string to see how RTD handles wrapping text. Yes indeedy, wrappy wrappy. Eggs and backups-y. 
	Here's the first text of the second descriptive line. CSS1_: Another helpful descriptive statement.
	
	ThirdLink_ | FourthLink_ | FifthLink_
	
	
	An indented flag ``Doc2008`` *Info*  
		920093_: more descriptions, dude. CSS2_: Moar tekts.
		
		ThirdLink_ | FourthLink_ | FifthLink_ 


Another flag ``Doc2008`` *Info*  
	920093_: descriptions before a warning.
	
	.. warning::
	
		This flag should not be used with toast and jam.
		
	ThirdLink_ | FourthLink_ | FifthLink_ 
	
	
	
.. hlist::
   :columns: 3

   * A list of
   * short items
   * that should be
   * displayed
   * horizontally
		
		
.. note::

   This function is not suitable for sending spam e-mails.
   
.. versionadded:: 2.5
   The *spam* parameter.
   
.. deprecated:: ``2016 SP1``
   Use the USE HINT argument "long_underscore_name"
   
   
.. seealso::

   Module :py:mod:`zipfile`
      Documentation of the :py:mod:`zipfile` standard module.

   `GNU tar manual, Basic Tar Format <http://link>`_
      Documentation for tar archive files, including GNU tar extensions.
	  
	  
.. seealso:: modules :py:mod:`zipfile`, :py:mod:`tarfile`	  


.. _920093: https://support.microsoft.com/en-us/kb/920093
.. _CSS1: https://blogs.msdn.microsoft.com/psssql/2016/11/15/unable-to-drop-a-user-in-a-database/
.. _CSS2: https://blogs.msdn.microsoft.com/psssql/2016/11/15/unable-to-drop-a-user-in-a-database/
.. _ThirdLink: http://www.python.org
.. _FourthLink: http://www.python.org
.. _FifthLink: http://www.python.org
		

Here is a normal paragraph containing *italic*, **bold**, `interpreted text`, ``inline literals``, 
standalone hyperlinks (http://www.python.org), external hyperlinks (Python_), internal cross-references
(example_), footnote references ([1]_), citation references ([CIT2002]_), substitution pictures 
(|D2014|), and _`inline internal targets`.

Multiple paragraphs are separated by blank lines and are left-aligned.

.. _Python: http://www.python.org

.. [1] A footnote contains body elements, consistently
   indented by at least 3 spaces.
   
.. [CIT2002] Just like a footnote, except the label is
   textual.
   
.. _example:

The "_example" target above points to this paragraph.



Here's an image: 

.. image:: Info_11pt.png


- Here's a standard bullet list. This one contains a hyperlink to Python_.
- This is the second item

- This is the third item, with a space between it and the second item (in the source)

- This is the fourth item, and has multiple lines.
	See, a second line!
	
- This is a fifth item, but the paragraph has probs because
the second line isn't indented enough to be equal to the "This" at its start.

#. This is an enumerated list
#. here's the second item. Here's a hyperlink to Python_.

Flag we are describing
	Here's the description of the flag. This contains a link to Python_.
	Here's a link in the second line: Python_.
	
	Another Flag (indented) 
		Further indentation to describe the second flag. Link: Python_.
		
		
:FieldList:		This is an example of a field list. Link to Python_.

:FieldList2:	Is this useful to me? I think Github renders this as a table, annoyingly.

				Here's a second paragraph for FieldList2. Link to Python_.


This line inserted to break up the field lists.

:Hello: This field has a short field name, so aligning the field
        body with the first line is feasible.

:Number-of-African-swallows-required-to-carry-a-coconut: It would
    be very difficult to align the field body with the left edge
    of the first line.  It may even be preferable not to begin the
    body on the same line as the marker.
				
				
				
Here's an option list: 

	-a  command-line option "a"
	-b file   another option with an argument
	--long    a long option
	--long=file  long options can have arguments also
	/V    DOS-style argument 
	
	
Literal blocks are either indented or line-prefix-quoted blocks,
and indicated with a double-colon ("::") at the end of the
preceding paragraph (right here -->)::

    if literal_block:
        text = 'is left as-is'
        spaces_and_linebreaks = 'are preserved'
        markup_processing = None
		
::
	This is a literal block but with no preceding text (just a double-colon).
		Look at the white-space preservation! Note what happens with links: Python_
	
			
Block quotes consist of indented body elements:

    This theory, that is mine, is mine. Link to Python_

    -- Anne Elk (Miss) Another link to Python_
	
	
Another top-level paragraph.

        This paragraph belongs to a second-level block quote.

    This paragraph belongs to a first-level block quote.  The
    second-level block quote above is inside this first-level
    block quote.


Simple table:

====================  ==========  ==========
Header row, column 1  Header 2    Header 3
====================  ==========  ==========
body row 1, column 1  column 2    column 3
body row 2            Cells may span columns
====================  ======================


Complex table:	

+-----------+---------------------------------------------------------------------------------+
| Flag      | Description                                                                     |
+===========+=================================================================================+
| 243       | |D2014| |Infor| Lots of text. Lots of text. Lots of text. Lots of text. Lots of |
|           | Lots of text. Lots of text. Lots of text. Lots of text. Lots of text. Lots of t |
+-----------+---------------------------------------------------------------------------------+
| 1483      | |D2014| |Infor|  Some text                                                      | 
+-----------+---------------------------------------------------------------------------------+
| 243       | |D2014| |Infor| Lots of text. Lots of text. Lots of text. Lots of text. Lots of |
|           | Lots of text. Lots of text. Lots of text. Lots of text. Lots of text. Lots of t |
+-----------+---------------------------------------------------------------------------------+
| **10205** | |D2014| |Infor| Lots of text. Lots of text. Lots of text. Lots of text. Lots of |
|           | Lots of text. Lots of text. Lots of text. Lots of text. Lots of text. Lots of t |
+-----------+---------------------------------------------------------------------------------+

