![Me](/img/me.jpg "Me")
# Emirlan Nurlan uulu
******

## Contacts
******
* __Location:__ Bishkek, Kyrgyzstan
* __Phone number:__ +996(507)08-11-81
* __Email address:__ nur.emirlan.02@gmail.com
* __Discord:__ @nuremirrz erzetq9lol#6034
* __GitHub:__ [GitHub][1]

[1]: https://github.com/nuremirrz  "My GitHub"

## About Me
******
##### I am a junior frontend developer. I want to delve into this area and become a real developer. I am ready to work tirelessly to achieve my goal.

## Skills
******
1. HTML, CSS(SASS, LESS)
2. JavaScript, jQuery, React (Basic)
3. Material UI, Bootstrap, canvas
4. GIT, GITHUB, Firebase
5. SQL, MySQL
6. Problem-solving skills

## Code Example
******
```
function uploadFile(file) {
    // chekking type of file
    if(!['image/jpg', 'image/png', 'image/jpeg', 'image/gif', 'image/heic','image/heif'].includes(file.type)) {
        alert('You can add only photo!');
        formImage.value = '';
        return;
    }
    // checking file size
    if(file.size > 2 * 1024 * 1024) {
        alert('You can add a file smaller than 2mb');
        return;
    }

    let reader = new FileReader();
    reader.onload = function(e) {
        formPreview.innerHTML = `<img src="${e.target.result}" alt="Photo">`;
    };
    reader.onerror = function(e) {
        alert('Error');
    };
    reader.readAsDataURL(file);
}
```
## Experience
******
*I hope that learning on your platform will be a great experience for my development*

## Education
******
* University: **Kyrgyz-Turkish Manas University**, Computer Engineering
* Courses: 
    * Makers
    * ITlogia
    * Result School

## Language
******
1. Kyrgyz (Native)    
2. Russian (Fluent)
3. English (Intermediate)
4. Turkish (C1)
