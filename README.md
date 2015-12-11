# Changes to be made (reference Sauce Account)
```
	export SAUCE_USERNAME=your_username
	export SAUCE_ACCESS_KEY=your_access_key
```

# Running the tests
to run: `mvn test`

# Selenium grid setup
>java -jar selenium-server-standalone-2.48.2.jar -role hub
>appium -p 4723 -bp 5723 --nodeconfig /AbsolutePath/node1.json --udid emulator-5554
>appium -p 4728 -bp 5728 --nodeconfig /AbsolutePath/node2.json --udid emulator-5556
