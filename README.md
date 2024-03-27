class xseven {
    constructor() {
        this.alias  = [ 'xseven', 'dev' ]
    }

    contact() {
        const discord  = 'xseven907'
        const telegram = 't.me/xseven907'
        const email    = 'bartlomajek23@o2.pl'
        
        return discord, telegram, email
    }

    life() {
        const age        = 17
        const occupation = 'Student'
        const hobbies    = [ 'Programming', 'Cracking' ]
        
        return age, occupation, hobbies
    }

    programming() {
        const languages         = [ 'Javascript (Node.js Framework)', 'Python', 'C#', 'TypeScript', 'JavaScript', 'Go' ];
        const learning          = [ 'C++' ];
        const ide               = 'Visual Studio Code', 'Visual Studio', 'DnSpy', 'dbg';

        const preferredLanguage = languages[0];

        return languages, learning, ide, preferredLanguage
    }
}

module.exports = xseven
