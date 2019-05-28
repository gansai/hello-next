# hello-next

1. We need to install some npm packages, including react, next, react-dom
2. Then we need to update package.json scripts tag with information for dev:, build: , start: as pointing to next js. ( next, next build, next start). Basically we are saying that next will take over for these commands
3. Next, we need to create a main page inside pages directory, index.js. Just create a simple React component and export it.
4. npm run dev => this will build code and start server at port: 3000 localhost. You can access in localhost:3000
5. How things are done under hood? next -> react -> reactdom -> virtual dom -> html & javascript.
