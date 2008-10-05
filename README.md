# Country and region select

Provides a simple helper to get an HTML select list of countries and regions. 
The list of countries comes from [iso-codes package]( http://svn.debian.org/wsvn/pkg-isocodes/trunk/iso-codes/iso_3166/iso_3166.xml?op=file&rev=0&sc=0) and follows [IBM Globalization guideline](http://www-01.ibm.com/software/globalization/topics/writing/references.jsp) to avoid culturally-sensitive issues in Taiwan and China.

This plugin is modified from Rails [country_select plugin](http://github.com/rails/country_select) 
and licensed under the [MIT](http://www.opensource.org/licenses/mit-license.php)

## Example

    country_select("user", "country_name")