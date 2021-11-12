Small script to clear undifined user from user.com contact list.
# Go to list of user and run the following script from console
```
stemp = document.querySelectorAll(".table__custom-row")

for (element of stemp){
  test =element.querySelector(".column--name");
  if (test.innerText == 'U\nundefined'){
      test =element.querySelector(".custom-control-label")
      test.click()
  }
}
```
