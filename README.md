# redir by katahiromz

[![AppVeyor Build status](https://ci.appveyor.com/api/projects/status/lg6nyqil9utjn961?svg=true)](https://ci.appveyor.com/project/katahiromz/redir)

This is `redir` by Katayama Hirofumi MZ.

`redir` is a Win32 command line tool to redirect 
standard input, standard output and standard error output.

It works on Windows 95/98/Me/2000/XP/Vista/7.

## Usage

Usage: `redir` `input_file` `output_file` `error_file` `program` `[parameters]`

The `input_file` parameter is the path name of an input file.
The `output_file` parameter is the path name of an output file.
The `error_file` parameter is the path name of an error file.

You can specify special device names (`NUL`, `CON` etc.) for `input_file`, `output_file` and/or `error_file`.

`output_file` and `error_file` can be the same path name.

## Contact Us

katayama.hirofumi.mz@gmail.com
