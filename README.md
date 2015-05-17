# untitled-dice

##### Live demo: https://untitled-dice.github.io

More info (including changelog and FAQ) in the bitcointalk.org thread: https://bitcointalk.org/index.php?topic=1062680

Untitled Dice is a bare-bones bitcoin dice casino built on top of the [Moneypot.com gambling API](https://www.moneypot.com/api-docs.html) that lets anyone run their own dice site by forking this project.

Since Moneypot handles the user accounts, betting, faucet, and chat, Untitled Dice does not need a server of its own. It's fully client-side (just some javascript files), so it can be hosted anywhere including Github.

Moneypot even handles the bankroll. Profits are split between you, Moneypot, and Moneypot's investors. See: <https://www.moneypot.com/investment>.

![Screenshot](http://i.imgur.com/dTwOR01.png)

## Run your own dice site

If you want to run your own dice casino, all you need to do is clone/fork this project, create an app at Moneypot (https://www.moneypot.com/apps/new), and set the `config.app_id` at the top of the `app.js` file.

## Host it on Github

1. Fork this project
2. Rename the repository from `untitled-dice.github.io` to `{YOUR_USERNAME}.github.io`
3. Edit the config at the top of `app.js`
4. Visit `https://{YOUR_USERNAME}.github.io`

## Run it locally (for development)

    cd untitled-dice
    npm install
    python -m SimpleHTTPServer 5000

Then visit <http://localhost:5000>

## License

MIT
