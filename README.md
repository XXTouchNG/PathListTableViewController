# PathListTableViewController

A simple path list viewer in Objective-C.

## Usage

```objective-c
PathListTableViewController *ctrl = [[PathListTableViewController alloc] initWithPath:[[NSBundle mainBundle] pathForResource:@"cydia" ofType:@"list"]];
ctrl.striped = YES;
ctrl.pullToReload = YES;
ctrl.tapToCopy = YES;
ctrl.pressToCopy = YES;
ctrl.showFullPath = YES;
ctrl.allowSearch = YES;
UINavigationController *navCtrl = [[UINavigationController alloc] initWithRootViewController:ctrl];
[self presentViewController:navCtrl animated:YES completion:nil];
```
