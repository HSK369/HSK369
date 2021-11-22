
Moralis.authenticate().then(function (user) {
    console.log(user.get('ethAddress'))
})
