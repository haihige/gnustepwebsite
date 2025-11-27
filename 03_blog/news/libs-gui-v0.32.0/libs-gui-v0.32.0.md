# libs-gui Release 0.32.0

This version adds binding support for NSBrowser, NSOutlineView and NSTableView. Plus the usual bunch of bug fixes.

- Add support for bindings in NSBrowser.
- Return top level object when loading .gorm files.
- Add bindings support to NSOutlineView,
- Add support for 10.6 item-based delegate methods to NSBrowser.
- Add NSMenuToolbarItem.
- Add view based rendering to NSTableView and NSOutlineView.
- Add code to NSTreeController.
- Fix display of icons if the home is a symlink.
- Make some ivars in NSView protected instead of package scoped.
- Fix CI pipeline.
- Revert \_updateFieldEditor: on NSTextFieldCell.
- GSTheme bug fix by Tom Sheffler tom.sheffler@gmail.com.
- Fix memory leaks in test code.
- Don't load nil filename in NSImageRep.
- Prevent flickering in NSClipView.
- Simplify ICU configuration.
- Move GSColorSliderCell into gui itself.
- Bugfix for NSMenuView.
- Fix single colum handling in NSCollectionView.
- Additional GSTheme method(s) for NSTabView.
- Modify NSComboBox to handle attributed strings.
- NSTextFieldCell: Decode placeholder string.
- Make white default selection highlight color for NSTableView.
- Implement showsresizeindicator.
- NSApplication: toggle menu item "Hide" title and action on user click.
- Add NSCellHitResult typedef, introduced in OSX 10.10.
- Make menu visiblity themable.
- Fix decoding alternateContents in NSButtonCell.
- Font Panel autosizing fix.
- Implement integerValue method in NSSliderCell.
- NSBox: use macro to decode NSInteger into enum.
- Fall back to pkgconfig for resolving libtiff.
- GSMemoryPanel: Only call GSDebug* in debug mode.
- Add APPKIT\_EXPORT\_CLASS, APPKIT\_EXPORT annotations for some GS*
classes.
- Push modal window to top later in process.
