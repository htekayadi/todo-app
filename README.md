# Todo App (React/Redux and Node)
A simple todo application that consumes the [Cosmic JS API](https://cosmicjs.com).  Built using React, Redux, and Node.js.

## Starting the app
1. Edit the config located in `client/config.js` to point to your Cosmic JS Bucket Slug
```javascript
export default {
  bucket: {
    slug: 'your-bucket-slug', // add your Bucket slug here
    type_slug: 'tasks',
    read_key: '', // add read key if added to Cosmic JS > Your Bucket > Settings
    write_key: '' // add write key if added to Cosmic JS > Your Bucket > Settings
  }
}
```
2. Start the app
```
npm start
```
3. Go to http://localhost:3000 to manage your Todos.
