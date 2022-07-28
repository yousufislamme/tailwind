# Before start your project follow this content 
> create `HTML` , `CSS` & `JS` file properly

* then your custome `tailwind.css` file add this code
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
* run this code
`````
npx tailwindcss init
`````
* And open your Terminal and wright this line
```
npx tailwindcss-cli build css/custome-tailwind.css -o build/tailwind.css
```
* add thispostcss autoprefixer line 
```
npm install -D tailwindcss postcss autoprefixer
```
> change script locaion this path `"dev": "vite"`

```
npx tailwindcss init -p
```
~ prettier autoprefiex install
```
npm install -D prettier 
```
```
npx prettier index.html --write
```
* Then delete `build/tailwind.css` file before `npm run dev`

* Live server
```
npm run dev
```
