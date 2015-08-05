# TableViewSelectionBugIOS8

Combination of deselectRowAtIndexPath + endEditing causes cell to stay selected forever. For some reason, number of sections and rows makes difference, seems like some kind of edge case in table view implementation. Reproducibable on iPhone 5 with iOS 8.4.
