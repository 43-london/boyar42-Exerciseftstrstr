# Exercise

```python
Exercise: ft_strstr
Allowed functions : None

Reproduce the behavior of the function strstr (man strstr).

Here’s how it should be prototyped :
char *ft_strstr(char *str, char *to_find); 

Your function should return a pointer to the first occurrence in the string str of any of the entire sequence of characters specified in to_find, or a null pointer if the sequence is not present in str. The terminating null characters are not compared. 

For example 
```
char str[50] = "Hello World";
printf("%s\n", ft_strstr(str, "World"));
--> Output should be "World"
```
```
# Submissions 
 git push your solution in this repo and hit /submit in Discord