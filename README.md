# boilerplate-app  
Install instructions: (requires [`hub`](https://hub.github.com/) installed, aliased as `git`)  
* `git clone git@github.com:jchlu/boilerplate-react-app.git NEW_PROJECT-NAME && cd $_`  
* `git create -p $_` (remove `-p` if repo doesn't need to be private)  
* `git remote set-url origin git@github.com:jchlu/$(basename $PWD).git`  
* `git push -u origin master`  
* `yarn install`  
* `yarn run serve`  
