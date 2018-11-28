## Syntax Glossaries

This references directory will provide a basic syntax glossary for each language taught at Treehouse. They aren't meant to be a tutorial or to offer instruction - the goal is a quick and easy syntax reference featuring descriptive variable names for students to use during their coursework. Glossaries or specific entries in glossaries should be linked to from teacher's notes and instruction steps in places where new syntax or concepts are taught.

Each entry in the glossary will link back to the specific video where the concept is taught and also to any related practice sessions. Any related entries should also be linked under the "See also" section.

Glossaries currently available:

- [Javascript](https://github.com/treehouse/References/blob/master/javascript.md)



## Glossary Entry Template

The glossaries are written in markdown, with each language glossary in its own .md file. Glossary entries should be alphabetical with an alphabetical table of contents at the top of the file. See here for [examples of the type of code](#code-sample-examples) to include in glossary entries. The basic format for each entry is as follows:


```markdown
# Entry Title/Concept
1 to 3 code samples demonstrating the concept with descriptive and educational variable names.

### Learn on Treehouse
[Course Title - Video Title](https://teamtreehouse.com/library/course-title)

### Practice on Treehouse
[Practice Session Title](https://teamtreehouse.com/library/practice-session-title)

##### See also
[related listing title](#related-listing-link)\
[related listing title](#related-listing-link)

```


## Code Sample Examples 

#### Example: Function

```javascript
function myFunction(parameter) {
    console.log(parameter);
}
```

#### Example: Array

```javascript
var myArray = [element1, element2, element3];
```

```javascript
var myArray = new Array();
```

#### Example: For loop

```javascript
for (let i = 0; i <= 10; i++){
    console.log(i);
}
```

#### Example: Ternary Operator & Statement

```javascript
<condition> ? <code if true> : <code if false>;
```

```javascript
x == y ? console.log('true') : console.log('false');
```

```javascript
var val = x == y ? true : false;
```
