# shuffle

Shuffle command

# SYNOPSIS

    % shuffle <arguments>
    % shuffle < text.txt

# DESCRIPTION

The shuffle command shuffles the input it is given and outputs it.

If provided with arguments it will randomly shuffle them and print them separated by spaces on one line.

Otherwise it will read standard input, shuffle each line and print to standard output.

# OPTIONS

NONE!

# CAVEATS

When reading in a file, this program must load the entire content of the file in memory.  For big files that might be bad.

# AUTHOR

Graham Ollis &lt;plicease@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2015 by Graham Ollis.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
