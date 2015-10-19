##Ext JS

 it just emulate OOPs.
 
*****

##Ext JS core methods

1. Ext.define()
2. Ext.create()
3. Ext.apply()
4. Ext.require()

*****

#Ext Core classess

 Ext-JS class system has set **pre-processor** and set of **post-processors**

1. **Ext.ClassManager** , which is responsible for creatting class and associte it with a name
2. **Ext.Base**, which is the base class, like in java java.lang.Object
3. **Ext.Class**, every classes of EXTJS represent by Ext.Class type. Simplarly in java java.lang.Class
   (When we use the Ext.define method to define a cl**ass we are in fact creating an in**stance of the Ext.Class class.)
4. **Ext.Element**, this class responsible for dealing with DOM
5. **Ext.DomQuery**, this class responsible for query dom element
6. **Ext.DomHelper**, used to create dom element and html fragment

******

# Ext UI-widget Classes



2. UI components has set of *lifecycle* events

UI component cross 3-phases(creation, render, destrection). each phase has several steps.

*****
# UI Widget Events

 Events are fired by either by user or lifecyle of a UI widget 

# UI Widget Classes

 **Ext.ComponentManager** - every component instance are registered with its id
 
    Ext.Component-> Ext.AbstractComponent,  as base class for all the ExtJS widget
    Ext.component.Container, - responsible for managing children and  arrange layout. it introduce 'items' property
       Ext.panel.Panel - one of the container, can contain panel and other ui widgets.
       Ext.panel.Tool - have 25 predefined icon
           Ext.window.Window, it subclass to Panel, it is floating panel
                 TabPanel
                 FormPanel
                 BasicForm
                      Field
                           TextField
                           TextArea
              FieldSet             
              ViewPort
              Window
                  MessageBox
              MixedCollection          
             DOCK
             Toolbar

****

# UI Layout Classes

    ComponentLayout
        AutoLayout
        CardLayout
        Fit
        Accordion
        HBoxs
        VBox
        Border
        Dock
        Field Component Layout ( replacement for FormLayout)

******
# EXT - JS - API.

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