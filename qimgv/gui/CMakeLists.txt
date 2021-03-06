## SOURCES FOR QIMGV GUI

target_sources(qimgv PRIVATE
    centralwidget.cpp
    contextmenu.cpp
    flowlayout.cpp
    idirectoryview.cpp
    mainwindow.cpp

    customwidgets/actionbutton.cpp
    customwidgets/clickablelabel.cpp
    customwidgets/contextmenuitem.cpp
    customwidgets/floatingwidget.cpp
    customwidgets/floatingwidgetcontainer.cpp
    customwidgets/iconbutton.cpp
    customwidgets/iconwidget.cpp
    customwidgets/keysequenceedit.cpp
    customwidgets/menuitem.cpp
    customwidgets/overlaywidget.cpp
    customwidgets/pathselectormenuitem.cpp
    customwidgets/sidepanelwidget.cpp
    customwidgets/slidehpanel.cpp
    customwidgets/slidepanel.cpp
    customwidgets/slidevpanel.cpp
    customwidgets/spinboxinputfix.cpp
    customwidgets/thumbnailview.cpp
    customwidgets/thumbnailwidget.cpp
    customwidgets/videoslider.cpp
    customwidgets/pushbuttonfocusind.cpp

    dialogs/resizedialog.cpp
    dialogs/scripteditordialog.cpp
    dialogs/settingsdialog.cpp
    dialogs/shortcutcreatordialog.cpp

    overlays/changelogwindow.cpp
    overlays/controlsoverlay.cpp
    overlays/copyoverlay.cpp
    overlays/cropoverlay.cpp
    overlays/floatingmessage.cpp
    overlays/floatingmessageproxy.cpp
    overlays/fullscreeninfooverlay.cpp
    overlays/fullscreeninfooverlayproxy.cpp
    overlays/imageinfooverlay.cpp
    overlays/imageinfooverlayproxy.cpp
    overlays/mapoverlay.cpp
    overlays/renameoverlay.cpp
    overlays/saveconfirmoverlay.cpp
    overlays/videocontrols.cpp
    overlays/videocontrolsproxy.cpp
    overlays/zoomindicatoroverlay.cpp
    overlays/zoomindicatoroverlayproxy.cpp

    panels/croppanel/croppanel.cpp
    panels/mainpanel/mainpanel.cpp
    panels/mainpanel/thumbnailstrip.cpp
    panels/sidepanel/sidepanel.cpp

    panels/infobar/infobar.cpp
    panels/infobar/infobarproxy.cpp

    viewers/documentwidget.cpp
    viewers/imageviewerv2.cpp
    viewers/videoplayer.cpp
    viewers/videoplayerinitproxy.cpp
    viewers/viewerwidget.cpp

    folderview/foldergridview.cpp
    folderview/folderview.cpp
    folderview/folderviewproxy.cpp
    folderview/thumbnailgridwidget.cpp
    folderview/filesystemmodelcustom.cpp
    folderview/treeviewcustom.cpp
    folderview/bookmarkswidget.cpp
    folderview/bookmarksitem.cpp
)

# UI Files

target_sources(qimgv PRIVATE
    contextmenu.ui

    dialogs/resizedialog.ui
    dialogs/scripteditordialog.ui
    dialogs/settingsdialog.ui
    dialogs/shortcutcreatordialog.ui

    overlays/changelogwindow.ui
    overlays/copyoverlay.ui
    overlays/floatingmessage.ui
    overlays/fullscreeninfooverlay.ui
    overlays/imageinfooverlay.ui
    overlays/renameoverlay.ui
    overlays/saveconfirmoverlay.ui
    overlays/videocontrols.ui

    panels/croppanel/croppanel.ui
    panels/sidepanel/sidepanel.ui

    panels/infobar/infobar.ui

    folderview/folderview.ui
)
