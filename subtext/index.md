# subtext

*a text processor*

I wrote *subtext* because I wanted to write multi-format documents. I wanted to write one “source file” and use it to produce HTML, LaTeX, and other format types. I also wanted a code generator that would help with Go’s lack of generics and streamline the maintenance of a large number of Terraform files in my day job.

Some typesetting systems which don't support Unicode,  for instance, use special character sequences to denote quotation marks and apostrophes.

The tex system of ''this is a double quoted string"". "This is single quoted'. The car's grill.

In subtext, version 0.0.1, quotation marks {single-quoted} and "{double-quoted}

When you can, simply use the Unicode characters for your quotation marks and apostrophes: “”‘’.

