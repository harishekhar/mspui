# mspui Search 
Issues to resolve
1. Binary search not working with case insensitive words
3. Relevence score cross check
4. Take into consideration the question and answer weightage 
5. Show only the search keyword answer not all answer


+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Input

1. Remove special character and search only numbers or string
2. Similary while performing binary search, make sure search array doesn't contain any special character. 


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Resoved Issues: 
1. Binary search returning first match but not occurance of the same word. eg. There is multiple occurance for sim but it returing only first one. [Solved]

2. Binary search not return results for all matches. eg. SIM, Is, Yeah, course [Solved: Sorting was not properly made]

3. Highlighter of the words after sorting [Solved 29Mar/6:30AM]