0.6.5 / 2014-02-03
  * Export `util`, which comes with the define-schema helper

0.6.4 / 2014-01-05
  * Fix plv8x not bootstrapped when client flag is specified

0.6.3 / 2013-12-18
  * Allow options in plv8x.new:
    * `client` flag to assume plv8x bootstrapped

0.6.2 / 2013-11-16
==================
  * Support array types for user-funcs

0.6.1 / 2013-11-06
==================
  * Use native pg

0.6.0 / 2013-10-28
==================
  * Support pg 9.3
  * polyfill row_to_json, array_to_json, to_json

==================
  * Fix object-style pg connection info

0.5.4 / 2013-08-06
==================
  * functions can now be marked to be imported in bootstrap stage

0.5.3 / 2013-07-25
==================
  * import-bundle-funcs

0.5.2 / 2013-07-10
==================
  * Restore pg 9.1 support
  * Update to use node-pg 2.1

0.5.1 / 2013-07-05
==================
  * add primary key to plv8x.code name
  * ignore pgrest and express when bundling

0.5.0 / 2013-06-22
==================
  * Update to use node-pg 2.0
  * Properly handle json return type, no more manual parse required

0.4.4 / 2013-06-21
==================
  * Fix -f with injected code that uses LiveScript primtives like $import
  * More reliable mk_func with existing functions being used in views
  * Allow specifying -f return type with a trailing colon
  * Fix -f functions without args

0.4.3 / 2013-05-08
==================
  * Restore support for PostgreSQL 9.0

0.4.2 / 2013-04-24
==================
  * Support injecting functions with callback callconv
  * Support injecting functions exported as root object

0.4.1 / 2013-04-24
==================
  * Fix importing module-name-with-dash (@selenamarie)

0.4.0 / 2013-04-21
==================
  * More helpful error message when --db is missing

0.3.4 / 2013-04-14
==================

  * Add -d alias for --db
  * Add -r and -e for eval in plv8x context
  * Add -c for executing queries
  * Add --json for json output
