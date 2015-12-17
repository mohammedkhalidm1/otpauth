## More to come soon ##

<br /><br /><h1>Proper functionality of hexstr2int</h1>
<font color='green'>Pass: </font>testNullParameter     <font color='gray'>Properly threw exception on null parameter at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 37]</font><br /><font color='green'>Pass: </font>testEmptyParameter     <font color='gray'>Properly threw exception on empty string parameter at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 48]</font><br /><font color='green'>Pass: </font>testIntegerParameter     <font color='gray'>Properly threw exception on integer parameter at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 58]</font><br /><font color='green'>Pass: </font>testArrayParameter     <font color='gray'>Properly threw exception on array parameter at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 71]</font><br /><font color='green'>Pass: </font>testNonHexString     <font color='gray'>Properly threw exception on non-hex string parameter at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 81]</font><br /><font color='green'>Pass: </font>testValidHexString     <font color='gray'>hex string AA9900 should convert to 11180288, converted to 11180288 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 91]</font><br /><font color='green'>Pass: </font>testValidShortHexString     <font color='gray'>hex string 05c should convert to 92, converted to 92 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 99]</font><br /><font color='green'>Pass: </font>testValid8DigitHexString     <font color='gray'>hex string 12345678 should convert to 305419896, converted to 305419896 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 108]</font><br /><font color='green'>Pass: </font>testValid10DigitHexString     <font color='gray'>hex string 123456789a should convert to 78187493530, converted to 78187493530 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 118]</font><br /><font color='green'>Pass: </font>testValid12DigitHexString     <font color='gray'>hex string 123456789abc should convert to 20015998343868, converted to 20015998343868 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 126]</font><br /><font color='green'>Pass: </font>testValid14DigitHexString     <font color='gray'>hex string 123456789abcde should convert to 5124095576030430, converted to 5124095576030430 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 134]</font><br /><font color='red'>Fail: testValid16DigitHexString -&gt; hex string 123456789abcdeff should convert to 1311768467463790300, converted to 1311768467463790335 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 142]<br />

</font><font color='green'>Pass: </font>testHexStringWithLeading0x     <font color='gray'>hex string 0x123456789a should convert to 78187493530, converted to 78187493530 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 150]</font><br /><font color='red'>Fail: testValid48DigitHexString -&gt; hex string fffffffffffffffffffffffffFFFFFFFFFFFFFFFFFFFFFFF should convert to 6.2771017353867E+57, converted to 6.2771017353867E+57 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 157]<br />
</font><font color='green'>Pass: </font>testValidHexStringWithUpperLowerAndNumeric     <font color='gray'>hex string 1aBcD5 should convert to 1752277, converted to 1752277 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 164]</font><br /><font color='green'>Pass: </font>testValidHexStringWithLeadingZero     <font color='gray'>hex string 01aBcD5 should convert to 1752277, converted to 1752277 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 172]</font><br /><font color='green'>Pass: </font>testValidHexStringWithTrailingZeros     <font color='gray'>hex string 01aBcD500 should convert to 448582912, converted to 448582912 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 179]</font><br /><table width='100%><tr><td' border='1'><font color='green'> <b>15</b> passes</font>, <font color='red'> <b>2</b> fails</font>, and <font color='red'> <b>0</b> unexpected exceptions.</font></table><br /><br /><h1>Proper functionality of binstr2int</h1>

<font color='green'>Pass: </font>testNullParameter     <font color='gray'>Properly threw exception on null parameter at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 196]</font><br /><font color='green'>Pass: </font>testEmptyParameter     <font color='gray'>Properly threw exception on empty string parameter at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 207]</font><br /><font color='green'>Pass: </font>testIntegerParameter     <font color='gray'>Properly threw exception on integer parameter at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 217]</font><br /><font color='green'>Pass: </font>testInvalidArrayParameter     <font color='gray'>Properly threw exception on array parameter at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 230]</font><br /><font color='green'>Pass: </font>testNonBinString     <font color='gray'>Properly threw exception on non-binary string parameter at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 240]</font><br /><font color='green'>Pass: </font>testValidBinString     <font color='gray'>bin string 101100 should convert to 44, converted to 44 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 249]</font><br /><font color='green'>Pass: </font>testValidBinStringWithTrailingB     <font color='gray'>bin string 101100b should convert to 44, converted to 44 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 258]</font><br /><font color='green'>Pass: </font>testValidShortBinString     <font color='gray'>bin string 1 should convert to 1, converted to 1 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 266]</font><br /><font color='red'>Fail: testValid32DigitBinString -&gt; bin string 111101100010101110011010110001101 should convert to 16133018, converted to 8260105613 at [/srv/www/htdocs/otpauth/tests/nutils_tests.php line 282]<br />

</font><table width='100%><tr><td' border='1'><font color='green'> <b>23</b> passes</font>, <font color='red'> <b>3</b> fails</font>, and <font color='red'> <b>0</b> unexpected exceptions.</font></table><br /><br /><h1>Tests ivcs dictionary and reverse arrays</h1>
<font color='green'>Pass: </font>testSizeIvcsArray     <font color='gray'>$ivcs array should be 2048 in length, is 2048 at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 24]</font><br /><font color='green'>Pass: </font>testSizeIvcsInverseArray     <font color='gray'>$ivcs array should be 2048 in length, is 2048 at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 36]</font><br /><font color='green'>Pass: </font>testIvcsAndReverseArrayEquivalence     <font color='gray'>$ivcs array and $rev_ivcs array should match at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 55]</font><br /><font color='green'>Pass: </font>testIvcsShortWords     <font color='gray'>$ivcs array words should be strings from 1 to 5 chars in length at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 94]</font><br /><table width='100%><tr><td' border='1'><font color='green'> <b>27</b> passes</font>, <font color='red'> <b>3</b> fails</font>, and <font color='red'> <b>0</b> unexpected exceptions.</font></table><br /><br /><h1>Transform array of hashes to IVCS six-word format</h1>

<font color='green'>Pass: </font>testEmptyArray     <font color='gray'>Properly threw exception on empty array at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 110]</font><br /><font color='green'>Pass: </font>testStringNotArray     <font color='gray'>Properly threw exception on improper data type (string) at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 119]</font><br /><font color='green'>Pass: </font>testIntNotArray     <font color='gray'>Properly threw exception on improper data type (int) at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 128]</font><br /><font color='green'>Pass: </font>testNullNotArray     <font color='gray'>Properly threw exception on null list at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 137]</font><br /><font color='green'>Pass: </font>testNullArrayItem     <font color='gray'>null item in the list should return a null item at same element at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 157]</font><br /><font color='green'>Pass: </font>testEmptyArrayItem     <font color='gray'>empty item in the list should return a null item at same element at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 177]</font><br /><font color='green'>Pass: </font>testNonStringArrayItem     <font color='gray'>integer item in the list should return a null item at same element at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 196]</font><br /><font color='green'>Pass: </font>testNonStringArrayItem2     <font color='gray'>item which is array in the list should return a null item at same element at [/srv/www/htdocs/otpauth/tests/ivcs_tests.php line 216]</font><br /><table width='100%><tr><td' border='1'><font color='green'> <b>35</b> passes</font>, <font color='red'> <b>3</b> fails</font>, and <font color='red'> <b>0</b> unexpected exceptions.</font></table><br /><br /><h1>IVCS transform attempts from hex data on invalid data</h1>

<table width='100%><tr><td' border='1'><font color='green'> <b>35</b> passes</font>, <font color='red'> <b>3</b> fails</font>, and <font color='red'> <b>0</b> unexpected exceptions.</font></table>