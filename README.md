# NAME

Deeme::Backend::Meerkat - MongoDB Backend using Meerkat for Deeme

# SYNOPSIS

    use Deeme::Backend::Meerkat;
    my $e = Deeme->new( backend => Deeme::Backend::Meerkat->new(
          database => "deeme",
          host     => "mongodb://localhost:27017",
          username=>"some",
          password=>"password"
      ) );

# DESCRIPTION

Deeme::Backend::Meerkat is a MongoDB Deeme database backend using Meerkat.
Only database and host are strictly required.

# AUTHOR

mudler <mudler@dark-lab.net>

# COPYRIGHT

Copyright 2014- mudler

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[Deeme](https://metacpan.org/pod/Deeme)
