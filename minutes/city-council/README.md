### DESCRIPTION
The City Council minutes datasets consist of the transcribed and proof-read text from the annually printed minutes. Text from one specific agenda item on one specific page produces one row. If the same agenda item runs across several pages, it just produces several rows of text.

Each row has the following columns:
- date_of_meeting

   The date of the meeting (yyyy-mm-dd)

- publication_page

   The original pagenumber from the printed minutes

- page_url

   Link to a scanned copy of the printed page

- record_ids

   One or more record_ids that the current agenda item references. The ids are assigned by the City Council

- text

   The transcribed text



### STATUS (2017-03-07)
The datasets currently contain unvalidated record_ids. They also lack the original subjects assigned to them by the City Counsil itself in accordance with their own home-spun thesaurus.



### ROADMAP
In a couple of weeks most record_ids will be validated. However, the datasets will continue to contain some unknown ids.

Furthermore, most agenda items will have the originally assigned subject(s) added.

Annually, as the minutes from one more year can be legally published, they will be added to the latest dataset.
