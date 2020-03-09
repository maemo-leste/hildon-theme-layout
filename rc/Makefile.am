layoutdir 				= ${datadir}/@PACKAGE@/

layout_DATA 				= gtkrc

RC_FILES				= afterincludes.rc 		\
					  afterthemespecificgtk.rc 	\
					  base.rc 			\
					  defaultarrows.rc 		\
					  gtkbutton.rc 			\
					  gtkbuttonbox.rc 		\
					  gtkcellview.rc		\
					  gtkcheckbutton.rc 		\
					  gtkcheckmenuitem.rc 		\
					  gtkdialog.rc 			\
					  gtkentry.rc 			\
					  gtkcombobox.rc 		\
					  gtkentrycompletion.rc 	\
					  gtkexpander.rc 		\
					  gtkframe.rc 			\
					  gtklabel.rc			\
					  gtkmenu.rc 			\
					  gtkmenuitem.rc 		\
					  gtkmenutoolbutton.rc 		\
					  gtknotebook.rc 		\
					  gtkpaned.rc 			\
					  gtkprogressbar.rc 		\
					  gtkradiobutton.rc 		\
					  gtkrange.rc 			\
					  gtkrc.rc 			\
					  gtkscale.rc           \
					  gtkscrollbar.rc 		\
					  gtkscrolledwindow.rc 		\
					  gtkseparator.rc 		\
					  gtksettings.rc 		\
					  gtktextview.rc 		\
					  gtktoggletoolbutton.rc 	\
					  gtktoolbar.rc 		\
					  gtktoolbutton.rc 		\
					  gtktreeview.rc 		\
					  gtkiconview.rc 		\
					  hildonwindow.rc 		\
					  hildoncandidatebox.rc 	\
					  hildoncaption.rc 		\
					  hildoncolorchooser.rc 	\
					  hildoncontrolbar.rc 		\
					  hildonnote.rc 		\
					  hildonnumbereditor.rc 	\
					  ossoapplicationinstaller.rc 	\
					  hildontimepicker.rc		\
					  hildonweekdaypicker.rc	\
					  themespecificgtk.rc		\
					  hildonthumbscrollbar.rc

gtkrc: $(RC_FILES)
	hildon-theme-rc-parser gtkrc.rc gtkrc

CLEANFILES				= gtkrc

MAINTAINERCLEANFILES			= Makefile.in 

EXTRA_DIST				= $(RC_FILES)
