********************************
Building a Simple User Interface
********************************
The graphical user interface for an Android app is built using a hierarchy of View and ViewGroup objects. 
View objects are usually UI widgets such as buttons or text fields. ViewGroup objects are invisible view 
containers that define how the child views are laid out, such as in a grid or a vertical list.

Android provides an XML vocabulary that corresponds to the subclasses of View and ViewGroup so you can define 
your UI in XML using a hierarchy of UI elements.
	
	.. image::  img/viewGroup.png
    :alt: Course image
	:align: center
	
	Create a Linear Layout
	----------------------
	**res/layout/activity_my.xml**
	.. note:: <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="horizontal" >
    </LinearLayout>
	
	LinearLayout is a view group (a subclass of ViewGroup) that lays out child views in either a vertical or 
	horizontal orientation, as specified by the android:orientation attribute. 
	
	Two other attributes, android:layout_width and android:layout_height, are required for all views in order 
	to specify their size.
	
	.. note:: **"match_parent"** This value declares that the view should expand its width or height to match the width or height of the parent view.

