# Business-Stripe-WebCheckout
Perl module to provide a simple way to implement payments using Stripe hosted checkout

VERSION 1.3 - 12th September 2022

This module allows items to be added to a 'Trolley'.  The Trolley and its contents are passed to [Stripe](https://stripe.com/gb) for payment using the Stripe hosted checkout.  For simple online sales this module provides a quick and easy way to collect payment without having to get involved in the nuances of the Stripe API.

Stripe will return from the hosted checkout on either `success-url` or `cancel-url` depending on the payment being successful.

[CPAN Documentaion](https://metacpan.org/release/BOD/Business-Stripe-WebCheckout-1.3/view/lib/Business/Stripe/WebCheckout.pm)
 
INSTALLATION
 
To install this module, run the following commands:
 
        perl Makefile.PL
        make
        make test
        make install
 
SUPPORT AND DOCUMENTATION
 
After installing, you can find documentation for this module with the
perldoc command.
 
    perldoc Business::Stripe::WebCheckout
 
You can also look for information at:
 
    RT, CPAN's request tracker (report bugs here)
        https://rt.cpan.org/NoAuth/Bugs.html?Dist=Business-Stripe-WebCheckout
 
    Search CPAN
        https://metacpan.org/release/Business-Stripe-WebCheckout
 
 
LICENSE AND COPYRIGHT
 
This software is copyright (c) 2022 by Ian Boddison.
 
This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
