# Scammer-Spammer
Spam those Scammers out of existence! but what?

This is an easy to use form spammer which can be edited however is needed to work for the different sites. It includes fake information sending, basic multi-threading and changing browser agent data. Feel free to edit the code and share how you want, credit appreciated.

Fake Information provided by [Fake Name Generator](https://www.fakenamegenerator.com "Fake Name Generator")

## Instructions
1. Configure the options you need at the top of the file.
```python
# Change configuration settings here.
config.zipFile = "fake-details.zip"
config.fakeDetailsFile = "FakeNameGenerator.com-100000-UK,US,AUS,CAN.csv"
config.fakeDetailsLength = 100000
config.multiThreading = True
config.multiThreads = 50
```
2. Add your target URL to the variable in the make_request function.
```python
url = 'https://scammer.com'
```
3. Configure your web request in the data variable. Use the person variable created from the fakePerson class to get your fake information (see example).
```python
data = {'username'=person.username,'password'=person.password}
```
5. Run and Attack!
