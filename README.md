html2csv
========

html2csv

Usage
=====

    <table id="datatable">
        <tr>
            <td>100</td> <td>200</td> <td>300</td>
        </tr>
        <tr>
            <td>400</td> <td>500</td> <td>600</td>
        </tr>
    </table>

    <a download="somedata.xls" href="#" onclick="return ExcellentExport.excel(this, 'datatable', 'Sheet Name Here');">Export to Excel</a>
    <a download="somedata.csv" href="#" onclick="return ExcellentExport.csv(this, 'datatable');">Export to CSV</a>
    
Compatibility
-------------

Firefox, Chrome

It does not work on Internet Explorer yet. Internet Explorer does not allow to use url data schema on links.

TODO
====

Make it work on Internet Explorer. Any ideas are welcome.

Notes
=====

IE8 or lower do not support *data:* url schema.
IE9 and upper do not support *data:* url schema on links.
