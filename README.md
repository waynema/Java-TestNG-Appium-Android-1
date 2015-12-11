
# Emulator setup
```
>android avd
>emulator @sauce
>emulator @appium
>adb devices
```

# Selenium grid setup
```
>java -jar selenium-server-standalone-2.48.2.jar -role hub
>appium -p 4723 -bp 5723 --nodeconfig /AbsolutePath/node1.json --udid emulator-5554
>appium -p 4728 -bp 5728 --nodeconfig /AbsolutePath/node2.json --udid emulator-5556
>appium -p 4828 -bp 5828 --nodeconfig /AbsolutePath/node3.json --udid 06df4e0e (real device)
```

# Running the tests
to run: `mvn test`
