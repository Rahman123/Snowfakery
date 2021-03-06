# Snowfakery History

In the beginning, programmers created the databases. Now the databases were formless and empty, and they had no data.

And so [Salesforce.org](http://salesforce.org/) said “Let there be data,” and there was Snowfakery. And it was good.

## Snowfakery 0.8.1

Snowfakery includes support for Salesforce RecordTypes.

Snowfakery can output SQL/JSON NULL using YAML blank fields or the YAML literal 'null'

Fields starting with __ are now properly suppressed as per the documentation.

Various performance and reliability improvements: 
 * parsed dates are now cached
 * Jinja values are always coerced to a string where appropriate
 * internal attributes were renamed for clarity
 * lookups are only generated in CCI mappings if they are actually needed

## Snowfakery 0.8.0

Snowfakery now specifies its install requirements with minimum versions rather than specific versions,
for improved compatibility with CumulusCI.

## Snowfakery 0.7

Windows compatibility improved, especially in test cases.

Changed the syntax for CSV handling.

Added --output-folder command.

## Snowfakery 0.6.1, 0.6.2, 0.6.3

Bugfixes (not user visible) and code cleanup.

## Snowfakery 0.6

Snowfakery 0.6 is open source!

## Snowfakery 0.5

The first version of Snowfakery was [Salesforce.org](http://salesforce.org/) internal-only.
