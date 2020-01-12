# react-native-jhipster-jwt-auth
React NAtive authentication into JHipster App using JWT

## Usage

Import it in your project

	import Auth from '../<folder>/Auth';

Login

	Auth.login('username', 'password').then( response => {
        console.log("Response: ", response);
        console.log("User: ", Auth.session.user);
    }

Account registration

	Auth.register('username', 'password', 'email@server.com').then( response => {
        console.log("Response: ", response);
        console.log("User: ", Auth.session.user);
    }

