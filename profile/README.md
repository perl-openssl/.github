## perl-openssl organization

There are quite a few OpenSSL based (XS) perl modules available on [metacpan.org](https://metacpan.org/search?size=50&q=OpenSSL).

Some of those modules are actively being supported, while others appear to have been abandoned.  In some cases there is no active git repository, while in others the repository is under someone's personal account.

This ogranization is my answer to the long term support/maintenance of OpenSSL based modules.  It is hoped that some of the active maintainers will consider joining this organization and assisting in the support for modules that they do not actively maintain.

Hopefully over the course of time any active members of this organization can obtain COMAINT on some or all of the modules that are maintained by this organization.

As time goes on, people lose interest or move on so having a git repository that can survive the loss of one particular person will hopefull make the transition of these modules easier.

A proven support structure will also make it easier for the PAUSE admins to consider grating COMAINT on a CPAN module should the module's author (FIRSTCOME) become unresponsive.

## So how can you help

### Join the organization and help

If you are an existing OpenSSL based module owner, or maintainer on CPAN, ask to join the organization.  You can offer assistance to users, fix bugs, etc.  XS is a specialized interface from Perl to C libraries so having experienced people on a team will help everyone.

### Consider moving your modules to the organization

On your next release, consider moving your OpenSSL based modules to this organization.

## Who is behind this Organization

[TIMLEGGE](https://metacpan.org/author/TIMLEGGE) and [WATERKIP](https://metacpan.org/author/WATERKIP).  Both support numerous modules on CPAN and have worked together on Crypt::OpenSSL::Verify and Crypt::OpenSSL::VerifyX509.  TIMLEGGE currently maintains seven OpenSSL based modules (some under this organization) and has contributed to numerous others.

## But xz...

The attack on xz was unfortunate and does unfortunately mean that more care must be taken in transfering ownership and granting permissions.  That being said, if you are an active Perl developer on CPAN and you are looking to help or transfer your module we can verify who you are fairly easily.  New developers showing up out of the blue will obviously need to have more vetting.
