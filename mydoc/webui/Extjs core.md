
## Ext JS core methods

1. Ext.define()
2. Ext.create()
3. Ext.apply()
4. Ext.require()
5. Ext.onReady() alias to Ext.EventManager.onDocumentReady();

# Ext Core classess

#### Ext JS 4.0 Class Ststem,

   * Dynamic class loading
   * multiple inheritance via mixin
   * dependency injection

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
|   **Ext.MessageBox**     |   it class name and its alias is **Ext.Msg**    |
| LocalStorageProxy | it store data in HTML 5 local storage, rather than ext js's store|
