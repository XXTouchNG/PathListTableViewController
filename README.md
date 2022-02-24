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

## Screenshots

<p float="left">
  <img src="/IMG_0015.PNG" width="32%">
  <img src="/IMG_0016.PNG" width="32%">
  <img src="/IMG_0017.PNG" width="32%">
</p>
