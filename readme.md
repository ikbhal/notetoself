# Note to Self
## Getting Started
1. Go to [Cosmic JS](https://cosmicjs.com) and create a new Bucket.
2. Download the Note to Self repo:
```
git clone https://github.com/cosmicjs/notetoself
yarn
```

## Starting the app
1. Edit the config part of `index.js` to point to your Cosmic JS Bucket Slug
```
config.bucket = {
  slug: 'your-bucket-slug', // add your slug here
  read_key: '',
  write_key: ''
}
```
2. Install the app globally
```
npm install -g
```
3. Anywhere view / create / edit / delete notes with the following command:
```
notetoself
```