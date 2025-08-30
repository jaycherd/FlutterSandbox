# Info
## What this
- me want to learn about flutter and then build something..

## Key points
- flutter work multi platform but must pick a target.. thinking to start with android get idea how it works on phone
- Dart, the programming language in which you're writing this app, is **null-safe**, so it won't let you call methods of objects that are potentially null. In this case, though, you can use the **! operator ("bang operator")** to assure Dart you know what you're doing. (displayMedium is definitely not null in this case. The reason we know this is beyond the scope of this codelab, though. context below:

```dart
    final style = theme.textTheme.displayMedium!.copyWith(
      color: theme.colorScheme.onPrimary,
    );
```


# Projects
## setup
* installed.. not sure if need the android sdk and what not.. maybe will come up if a project calls for it.. do want to get into mobile stuffs so im sure just have to find the right guide

## TestDrive
- Hot reload kinda dope.. reloads and saves state
    - works well on vscode if run through Run -> Start Debugging and can use the flutter inspector from flutter sidebar in devtools
    - also easier to do the hot reload and restart

## Next?
keep going from https://docs.flutter.dev/get-started/quick; made it to part 6 add functionality of first flutter app: https://codelabs.developers.google.com/codelabs/flutter-codelab-first#5
- i think start with
    - learn flutter development (these all seem pretty good)
        - write your first app
        - learn the fundamentals (maybe do this first..?)
        - discover flutter widgets
        - explore samples and tutorials
- then i could see how to integrate to android or ios; same url as above
    - build for other platforms could be cool
        - android / ios
