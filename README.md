Intruduction to MultiselectV2-widget
===========================================
@date:2013-8-20

@author: Ma Xiupeng(RocShow)

I forked this repository from jquery-ui-multiselect-widget(http://www.erichynds.com/jquery/jquery-ui-multiselect-widget/). Then I renamed it as MultiselectV2, because we still need to use the original widget in our projects. 

What did I Change
--------------------------------------------
- Fixed A bug in IE
There is one bug in the original version. That is in IE(I tested in IE 8 and 7), when I choose one selection and refresh the page, all the selections will be selected. 

I fixed this bug in my repository.

- Fixed A bug about menu's location
When the number of selected selections increase, the button label need to display more words. The text can be arranged in several lines. Under this situation, when the menu is opened, it will overlap with the button label. That means its location cann't be modified along with the height of the button label. 

I fixed this bug in my repository.

- Added a new option `defaultSelected`
Data type of this option is Array and each element need to be an integer. As its name implies, this option means which selections (represent by their indexes) should be selected initially.

- Added a new option `labelFontSize`
So the font size of the label of the widget can be custom manually instead of modify css files. 

- Selected selections will be shown as the title attribute of the button label.

Some more changes are underway...
---------------------------------------------