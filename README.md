# Go to list of user and run the following script from console

stemp = document.querySelectorAll(".table__custom-row")

for (element in stemp){
  test =element.querySelector(".column--name")
  if (test.innerText == 'U\nundefined'){
      test =element.querySelector(".custom-control-label")
      test.click()
  }
}
