# Country and region select

Provides a simple helper to get an HTML select list of countries and regions. 
The list of countries comes from [iso-codes package]( http://svn.debian.org/wsvn/pkg-isocodes/trunk/iso-codes/iso_3166/iso_3166.xml?op=file&rev=0&sc=0)

This plugin is modified from official Rails [Country select plugin](http://github.com/rails/country_select/tree/master) ([why?](http://hlb.yichi.org/blog/2008/09/22/258))
and licensed under the [MIT](http://www.opensource.org/licenses/mit-license.php)

## Example

    country_select("user", "country_name")