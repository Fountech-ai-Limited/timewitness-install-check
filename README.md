# A repository that installs TimeWitness

It builds an archive, installs the TimeWitness Action in one line, and publishes the archive, its
receipt and a provenance statement carrying a second receipt as a release, so anybody can download
all three and check both receipts with no account.

The line is whatever the README of the latest TimeWitness release tells you to write, read afresh on
every run, so a new release is installed here within six hours of it shipping and with no edit to
this repository. Each run then downloads what it published and checks it with no token, built from
the source of the same release: both receipts are verified, a one-bit change to the archive and to the
receipt in the provenance are each refused, and the format the provenance names has to be the one
that receipt's own bytes carry.

Nothing here is TimeWitness except the one line the workflow installs.
