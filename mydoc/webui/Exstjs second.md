##Ext JS

 it just emulate OOPs.

##Ext JS core methods

1. Ext.define()
2. Ext.create()
3. Ext.apply()
4. Ext.require()


#Ext Core classess

 Ext-JS class system has set **pre-processor** and set of **post-processors**
 
| CLASS | desc |
|--------|--------|
|   **Ext.ClassManager**     |   which is responsible for creatting class and associte it with a name     |
|   **Ext.Base**     |   which is the base class, like in java java.lang.Object     |
|   **Ext.Class**     |   every classes of EXTJS represent by Ext.Class type. Simplarly in java java.lang.Class. (When we use the Ext.define method to define a cl**ass we are in fact creating an in**stance of the Ext.Class class.)     |
|   **Ext.Element**     |    this class responsible for dealing with DOM     |
|   **Ext.DomQuery**     |   this class responsible for query dom element     |
|   **Ext.DomHelper**     |   used to create dom element and html fragment    |
|   **Ext.ComponentQuery**     |   use to query DOM tree using selector    |

# Ext Application specific class

| Class Name | desc |
|--------|--------|
|     **Ext.app.Application**    |  introduced in ExtJS 4, as application entry poiont, give application name space      |
|     **Ext.app.Controller**    |  it is base controller    |
|     **Ext.data.Model**    |  it is base model    |
|     **Ext.app.Store**    |  it is base store    |
|     **Ext.app.EventBus**    |  it is the event bus. that manage all the event occured in application.  |


# UI Widget Classes

| Class Name | className | class Name |  |Description|
|------------|-----------|------------|--|-----------|
|   **Ext.ComponentManager**     		  |        | |                                                       | every component instance are registered with its id |
|   Ext.Component-> Ext.AbstractComponent |        | |                                                       | as base class for all the ExtJS widget |
|     									  |  Ext.component.Container | 	   |        | responsible for managing children and  arrange layout. it introduce 'items' property |
|      									  |                          | Ext.tab.Panel |                       | this panel act as container for tabs|
|      									  |                          | Ext.panel.Panel |                     |one of the container, can contain panel and other ui widgets|
|      									  |                          | Ext.grid.Panel |                      |it is just grid container.|
|       								  |                          |                 | Ext.form.Panel		 | this can have any of form field to get user input |
|       								  |                          | Ext.panel.Tool          | 					 | have 25 predefined icon |
|       								  |        					 |                 		   |  Ext.window.Window, | it subclass to Panel, it is floating panel |
|       								  |        					 | Ext.container.ViewPort  |     | it occupy entier brower window and listen for resize events |
|       								  |        					 | Ext.container.Container |     | it used as container |
|       								  |        					 | Ext.form.field.Field    |     					| act as super class for base class |
|       								  |        					 | Ext.form.Lable          |     					| act as super class for  base class |
|       								  |        					 | Ext.form.field.Base     |     					| it is base class for all UI widgets|
|       								  |        					 |                         | Ext.form.field.Text  	| responsible for manage text value |
|       								  |        					 |                         | Ext.form.field.Number   | responsible for manage number value |

# UI Layout Classes

| class Name |    Class Name |   |Description|
|------------|---------------|---|-----------|
|ComponentLayout | | | |
| 			 | AutoLayout    |   |           |
| 		     | CardLayout    |   |           |
| 			 | Fit   		 | 	 | 			 |
| 			 | Accordion     |   |           |
| 			 | HBoxs    	 |   |           |
| 			 | VBox     	 |   |           |
| 			 | Border     	 |   |           |
| 			 | Dock     	 |   |           |
| 			 | Field Component Layout ( replacement for FormLayout)  | | |

# UI Widget Events

*  Events are fired by either by user or lifecyle of a UI widget 
*  UI components has set of *lifecycle* events
*  UI component cross 3-phases(creation, render, destrection). each phase has several steps.

# EXT - JS - API.

| API | description |
|--------|--------|
| Ext.util.Observable      |    it is used in UI Event handline , All the UI widgets are extend this class   |


1. FloatingManager
2. 
3. 
5.     
4. ComponentQuery
    


13. Store
14.     Model
15.         Association
22.         Validation
15.     Sorter
16.     Filter
17.     Grouper
18.     Proxy
19.         Reader
20.         Writer
21.     
23.     