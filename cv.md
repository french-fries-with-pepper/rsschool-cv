# Alexey Antonov  
## Contact Information  
Alexey_S_Antonov@protonmail.com  
[github profile](https://github.com/french-fries-with-pepper)  
## Skills  
### Front-end strack:  
- html  
- css  
- BEM
- javascript  
- typescript  
- React  

Have knowledge about html5, use css3(pure or with preprocessors like SCSS), well know JavaScript(es6+), can use build tools like webpack or gulp for optimization work process. Also have base experience in work with React.  
### Others:  
- git  
- unix  
- bash
- C  
- C++  
- Golang   

Have minor experience in system development (POSIX). Prefer using Linux as main OS.  

## Some code example  
```C
/* like split() in JS*/
char ** getTokens( const char *str,  const char * delim)
{
    /*init*/
    char * copy;
    copy = malloc((strlen(str)+1)*sizeof(char));
    /*strtok will move copy pointer, so we need keep it to free*/
    char * copySave = copy; 
    strcpy(copy,str);
    char **result;
    result = (char**)malloc(MAX_TOKENS*sizeof(char*));
    for (size_t i = 0; i < MAX_TOKENS; ++i)
    {
        result[i] = NULL;
    }  
    /*start spliting*/
    int i =0;
    char * token = strtok(copy, delim);
    while (token!=NULL){
        result[i] = (char*)malloc((strlen(token) + 1)*sizeof(char));
        result[i]=strcpy(result[i], token);
        ++i;
        token = strtok(NULL, delim);
    }
    result[i] = NULL;
    /*free memory*/
    free(token);
    free(copySave);

    return result;
}
```  
## Work experience  
***  
## Education  
- [HackerRank Problem Solving Advanced](https://www.hackerrank.com/certificates/4e6444b42d69)  
- [Computer Science Center Основы программирования для Linux](
https://stepik.org/cert/288658)  
- [HackerRank profile](https://www.hackerrank.com/alexey_s_antonov)  
- [Stepik profile](https://stepik.org/users/163260827)  

## English  
A2 level  

