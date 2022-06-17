Quill editor's dropdown stops working after the component is toggled by v-if.

It works fine in development mode but not in production.

![quill-bug](https://user-images.githubusercontent.com/51456572/174255639-de0856b8-b0d6-4335-9332-767507893dbd.gif)

1. git clone https://github.com/ga676005/quill-bug.git
2. npm i
3. npm run build
4. npm run preview
5. open the page
6. click the toggle button to show Editor, notice the dropdown is clickable
7. click the toggle button twice to hide and show Editor again, now dropdown is not clickable
