# gitflow

Usage from Terminal:

`./release.sh 1.0.0`
`./release.sh 1.5.7`

Some things to note:

* Line 7 specifies that your tag names will include a 'v' before the number. Remove the 'v' if desired.
* Lines 18 must point to a valid file path
* Line 22 expects to find text like "= v1.3.6", and will replace the number with the one you specified as an argument. Modify sed command as necessary/desired.
