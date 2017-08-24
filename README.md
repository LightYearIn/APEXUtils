# APEXUtils
Utilities developed for APEX in Force.com platform

Utility 1: clsFormatCurrency 
Description: Pass an unformatted Decimal in String format (for example, 1234567890.0123) and get it formatted with User's Locale specific Currency Symbol, Thousand Delimiter and Decimal Point Delimiter 

Input: 1234567890.0123

Method Call:
  String sValue = '1234567890.0123';
  System.debug(clsFormatCurrency.FormatCurrencyByCurrentUserLocale(sValue, true));

Output: EUR 1.234.567.890,0123
