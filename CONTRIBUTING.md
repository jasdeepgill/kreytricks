# CONTRIBUTING

This is set of standards to be used in contribution

### Indentation one TAB (Not effective yet)
Since winetricks is using indentation of four spaces which is conflicting with preference of others we decided to use tabs that can be resized in text editors to user preference

### Code Style (Not effective yet)
Winetricks is using allman style for shell script which is horrible thus we are using the 'K&R variant: 1TBS' (https://en.wikipedia.org/wiki/Indentation_style#Variant:_1TBS_(OTBS))

Example:

```sh
# Wrong
func()
{
	something
}
# Correct
func(){
	something
}
```
