# CodeFresh beautify example plugin

The purpose of this example is to show how to write simple Orion plugin, extend it and work with it
In this example we have developed very simple JS beautify plugin that will add menu item to run it on the selected text of document.
Also using Orion settings mechanism to extend the user experience by letting him select how to use the beautify logic.

## Code It

You can use CodeFresh system in order to start coding in just one click.
Just open account in CodeFresh, add this repository, click code it and you are in the game.

## Install Your plugin
Once you downloaded the git repository or opened it in CodeFresh code, open terminal and run the following:
npm install
npm start

If you are running local you will need the following URL:

[http://localhost:9000/](http://localhost:9000/)

If you are running using CodeFresh use the following URL:

[http://......./](http://......./)

You will now need to get into Orion editor, if you are in CodeFresh you are already inside one, otherwise you can use
[http://orionhub.org](http://orionhub.org), open account.

Get into the settings page, then into the plugins category, click the install button, put your URL and approve it.

## Test It

You plugin is now installed, get into the editor, open JS file, add some content.
Once you would like to beautify it, just click Tools>Beautify and it should see that the code is getting arranged.

## Update plugin

If you are only updating the plugin logic, all you have to do is refresh your page and the changes will get into effect.
If you would like to add/remove/update Orion extension points, you will need to get into the plugins page and click the refresh button on our specific plugin.

