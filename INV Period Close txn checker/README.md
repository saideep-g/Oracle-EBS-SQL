# [INV Period Close txn checker](https://www.enginatics.com/reports/inv-period-close-txn-checker/)
## Description: 
** Queries Used to Display the Counts in the Inventory Account Periods form  (Doc ID 357997.1)**
The following Blitz Report mimicks the counts found in the Inventory Accounting Period close form. 
1. The following parameters are used:
OrgID -- The Organization id.
StartPeriodDate -- The start period date for the period in question.
EndPeriodDate -- The end period date for the period in question.
2. The following SQL can be used to find the organization id:
select a.organization_id, b.organization_code, a.name
from HR_ALL_ORGANIZATION_UNITS_TL a, mtl_parameters_view b
where a.organization_id = b.organization_id
order by organization_id, organization_code **/
## Categories: 
[Enginatics](https://www.enginatics.com/library/?pg=1&category[]=Enginatics), [Toolkit - Operations](https://www.enginatics.com/library/?pg=1&category[]=Toolkit+-+Operations), [Toolkit - Setup & Support](https://www.enginatics.com/library/?pg=1&category[]=Toolkit+-+Setup+%26+Support)
## Dependencies
If you would like to try one of these SQLs without having Blitz Report installed, note that some of the reports require functions from utility package [xxen_util](https://www.enginatics.com/xxen_util/true).
# [Blitz Report™](https://www.enginatics.com/blitz-report/) import options
[rep_INV_Period_Close_txn_checker.xml](https://www.enginatics.com/xml/inv-period-close-txn-checker/)
# Oracle E-Business Suite - Reporting Library 
    
We provide an open source EBS operational and project implementation support [library](https://www.enginatics.com/library/) for rapid Excel report generation. 

[Blitz Report™](https://www.enginatics.com/blitz-report/) is based on Oracle EBS forms technology, and hence requires minimal training. There are no data or performance limitations since the output files are not generated through the XML mechanism. 

Standard Oracle [BI Publisher](https://www.enginatics.com/user-guide/#BI_Publisher) and [Discoverer](https://www.enginatics.com/blog/importing-discoverer-worksheets-into-blitz-report/) reports can also be imported into Blitz Report for immediate translation to Excel. Typically, reports can be created and version tracked within hours instead of days. The concurrent request output automatically opens upon completion without the need for re-formatting.

![Running Blitz Report](https://www.enginatics.com/wp-content/uploads/2018/01/Running-blitz-report.png) 

You can [download](https://www.enginatics.com/download/) and use Blitz Report [free](https://www.enginatics.com/pricing/) of charge for your first 30 reports.

The installation and implementation process usually takes less than 1 hour; you can refer to our [installation](https://www.enginatics.com/installation-guide/) and [user](https://www.enginatics.com/user-guide/) guides for specific details.

If you would like to optimize your Oracle EBS implementation and or operational reporting you can visit [www.enginatics.com](https://www.enginatics.com/) to review great ideas and example usage in [blog](https://www.enginatics.com/blog/). Or why not try for yourself in our [demo environment](http://demo.enginatics.com/).

© 2020 Enginatics