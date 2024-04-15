# a1ranger
All you wanted to do with "A1:D5" ranges

Dist folder has a [compatible ES-5 code](https://github.com/Max-Makhrov/a1ranger/blob/master/dist/Code.js), can be used from both back-, and front-end.

```
function test_ranger() {
  const ranger = new Ranger_("A1:B25");
  const grid = ranger.grid();
  if (!grid) {
    console.log(ranger.validation().message);
  } else {
    console.log(JSON.stringify(grid, null, 2));
  }
}

```
