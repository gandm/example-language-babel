// es6 default & rest params
var fn = function (options, delay = 5000, ...rest) {
    // es6 destructuring
    var { name, age, personality } = options;

    setTimeout(function () {
        console.log('logged with default timeout unless provided');
        console.log('you also passed in: ' + rest.length + 'extra params, auto bundled in to an array');
    }, delay);

    // es6 enhanced object literals
    return {
        name,
        age,
        getPersonality () {
            return 'My personality is: ' + personality;
        }
    };
};
