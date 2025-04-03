# dev-easy-group-project

## authors:

I stole this from ...

<a href="" target="">github</a> 

### here a cool :cool: code example

```javascript
function search_fact() {
    let input = document.getElementById('searchBar').value
    input = input.toLowerCase();
    let x = document.getElementsByClassName('card-body');

    for (i = 0; i < x.length; i++) {
        if (!x[i].innerHTML.toLowerCase().includes(input)) {
            x[i].style.display = "none";
        }
        else {
            x[i].style.display = "list-item";
        }
    }

```
this wasn't working, so i did this



```diff
function search_fact() {
-    let input = document.getElementById('searchBar').value
+   let input = document.getElementById('searchBar').value
    input = input.toLowerCase();
    let x = document.getElementsByClassName('card-body');

    for (i = 0; i < x.length; i++) {
        if (!x[i].innerHTML.toLowerCase().includes(input)) {
            x[i].style.display = "none";
        }
        else {
            x[i].style.display = "list-item";
        }
    }

```


<details>
  <summary>
    ## About this project
  </summary>
  - This was a class project to ... collab ..  data ... 
</details>

Easy group 3 working on a fact for all students in the class
# The group that worked on this was Carson Kerr, Reed Willis, Tatum Duthu, and Cohen Cantrell
