# unittest.mock
## description:
mock is a way to test your function with out having any side effect 
for example if you want to write a code to delete some file and you don't want to touch any of your valuable files during testing 
mock is going to help you to do that so it wil simulate that you removing the file is exist 
as you can see in mock_test.py file we were trying to delete somefile1.txt but it will not rely be deleted and the test still passed

## objectives:
the participants will learn:
- use os library to delete and check system files
- use unittest mock to test functions without side effect 

## no mock test:
the code will try to create file to test if rm function would delete it by checking if the file still exist after running the rm function

## mock test:
will simulate that the path of the file is right and run rm function to check if it will delete file somefile1.txt and we will notice that the file still there and will not be deleted