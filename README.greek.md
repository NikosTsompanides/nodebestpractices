[✔]: assets/images/checkbox-small-blue.png

# Node.js Βέλτιστες Πρακτικές

<h1 align="center">
  <img src="assets/images/banner-2.jpg" alt="Node.js Best Practices">
</h1>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/⚙%20Item%20count%20-%20101%20Best%20Practices-blue.svg" alt="101 items"> <img src="https://img.shields.io/badge/%F0%9F%93%85%20Last%20update%20-%20March%2012%202020-green.svg" alt="Last update: March, 2020"> <img src="https://img.shields.io/badge/ %E2%9C%94%20Updated%20For%20Version%20-%20Node%2012.12.0-brightgreen.svg" alt="Updated for Node 13.1.0">
</div>

<br/>

[![nodepractices](/assets/images/twitter-s.png)](https://twitter.com/nodepractices/) **Ακολουθήστε μας στο Twitter!** [**@nodepractices**](https://twitter.com/nodepractices/)


<br/>

Διαθέσιμες μεταφράσεις: [![CN](/assets/flags/CN.png)**CN**](/README.chinese.md), [![BR](/assets/flags/BR.png)**BR**](/README.brazilian-portuguese.md), [![RU](/assets/flags/RU.png)**RU**](/README.russian.md), [![PL](/assets/flags/PL.png)**PL**](/README.polish.md) [(![ES](/assets/flags/ES.png)**ES**, ![FR](/assets/flags/FR.png)**FR**, ![HE](/assets/flags/HE.png)**HE**, ![KR](/assets/flags/KR.png)**KR** και ![TR](/assets/flags/TR.png)**TR** σε εξέλιξη!)](#translations)

<br/>

###### Τη δημιουργία επιμελήθηκε η [Steering Committee](#steering-committee) και οι [Collaborators](#collaborators)

# Τελευταία νέα και βέλτιστες πρακτικές

- **:tada: Οι βέλτιστες πρακτικές για Node.js έφτασαν τα 50k αστέρια**:
Ευχαριστούμε όλους όσους συνεισέφεραν στο να φτάσει αυτό το έργο εδώ που βρίσκεται σήμερα. Έχουμε πολλά σχέδια για το μέλλον, καθώς επεκτείνουμε τη συνεχώς αναπτυσσόμενη λίστα βέλτιστων πρακτικών του Node.js.

- **🎧 Podcast**: Ο Yoni Goldberg από την ομάδα μας συμμετείχε στο τελευταίο επεισόδιο JS Party Podcast (Πολύ cool!) Για να μιλήσει για τις βέλτιστες πρακτικές του Node.js [🎧 Ακούστε Εδώ](https://changelog.com/jsparty/139)

- **:whale: Βέλτιστες πρακτικές Node.js + Docker**:
Μόλις κυκλοφορήσαμε την ενότητα Docker με Node.js που περιλαμβάνει 15 κουκκίδες για καλύτερες τεχνικές προγραμματισμού με το Docker

- **🎤 Ομιλία στο OdessaJS**: Θα μιλήσουμε για τη δοκιμή Node.js λογισμικού αυτήν την εβδομάδα στο υπέροχο [OdessaJS συνέδριο](https://odessajs.org/)

<br/><br/>

# Καλως ήρθατε! 3 πράγματα που πρέπει να γνωρίζετε πρώτα.

**1. Στην πραγματικότητα, διαβάζετε δεκάδες άρθρα για βέλτιστες πρακτικές με Node.js -** αυτό το repository είναι μια σύνοψη του κορυφαίου περιεχομένου σχετικά με τις βέλτιστες πρακτικές του Node.js, καθώς και του περιεχομένου που γράφτηκε εδώ από συνεργάτες.

**2. Είναι η μεγαλύτερη συλλογή και αυξάνεται κάθε εβδομάδα -** Προς το παρόν, περισσότερες από 80 βέλτιστες πρακτικές, οδηγοί σύνταξης και συμβουλές δόμησης κώδικα βρίσκονται εδώ. Νέα issues και pull requests δημιουργούνται καθημερινά για να κρατάνε αυτό το "βιβλίο" ενημερωμένο.Θα ήταν τέλειο να σας βλέπαμε να συνεισφέρετε είτε διορθώνοντας λάθη στον κώδικα  που βρίσκετε εδώ είτε βοηθώντας με τις μεταφράσεις, είτε προτείνοντας νέες ιδέες. Δείτε τους [τρόπους συγγραφής εδώ](/.operations/writing-guidelines.md)

**3. Οι περισσότερες βέλτιστες πρακτικές έχουν επιπλέον πληροφορίες -** Οι περισσότερες κουκκίδες συμπεριλαμβάνουν έναν σύνδεσμο **🔗Διαβάστε Περισσότερα** ο οποίος επεκτείνει την γνώση με παραδείγματα κώδικα αποσπάσματα από επιλεγμένα ιστολόγια και περισσότερες πληροφορίες.

<br/><br/>

## Πίνακας Περιεχομένων

1. [Πρακτικές Δόμησης Έργων Λογισμικού (5)](#1-project-structure-practices)
2. [Πρακτικές Διαχείρισης Σφαλμάτων (11) ](#2-error-handling-practices)
3. [Πρακτικές Σύνταξης Κώδικα (12) ](#3-code-style-practices)
4. [Πρακτικές Ελέγχου και Διασφάλισης Ποιότητας (13) ](#4-testing-and-overall-quality-practices)
5. [Going To Production Practices (19) ](#5-going-to-production-practices)
6. [Πρακτικές Ασφάλειας (25)](#6-security-best-practices)
7. [Πρακτικές Επιδόσεων (2) (Σε εξέλιξη ✍️)](#7-draft-performance-best-practices)
8. [Πρακτικές Docker (15)](#8-docker-best-practices)

<br/><br/>

# `1. Πρακτικές Δόμησης Έργου Λογισμικού`

## ![✔] 1.1 Διαχώρισε τον κώδικα σου σε components

**Συνοπτικά:** Το μεγαλύτερο πρόβλημα σε μεγάλα έργα λογισμικού είναι η συντήρηση προυπάρχον κώδικα με εκατοντάδες εξαρτήσεις σε βιβλιοθήκες τρίτων. Αυτό το εμπόδιο επιβραδύνει τους προγραμματιστές καθώς προσπαθούν να ενσωματώσουν νέες λειτουργίες στην εφαρμογή. Αντ'αυτού διαχωρίστε τον κώδικα σας σε components, από τα οποία το καθ'ένα θα έχει τον δικό του φάκελο και θα συντηρεί τον δικό του κώδικα και διασφαλίστε ότι ο κάθε component θα έχει απλή δομή και μικρό μέγεθος. Πατήστε στον σύνδεσμο 'Διαβάστε Περισσότερα' για να δείτε παραδείγματα σωστής δόμησης έργων λογισμικού.

**Διαφορετικά:** Όταν οι προγραμματιστές, που προσθέτουν νέες λειτουργίες στην εφαρμογή, αδυνατούν να κατανοήσουν το αντίκτυπο της προσθήκης/αλλαγής τους στον υπάρχοντα κώδικα και φοβούνται μήπως επιρρεάσουν άλλα εξαρτώμενα μέρη του, η ταχύτητα της διαδικασίας παραγωγής λογισμικού μειώνεται και το ρίσκο μεγαλώνει. Επιπλέον εκτιμάται πως η κλίμακα ανάπτυξης του κώδικα μειώνεται όταν αυτός δεν είναι διαχωρισμένος σωστά.
🔗 [**Διαβάστε Περισσότερα: Διαχώρισε τον κώδικα σου σε components**](/sections/projectstructre/breakintcomponents.md)

<br/><br/>

## ![✔] 1.2 Διαχωρείστε τα components σε επίπεδα, κρατήστε το επίπεδο διαδικτύου (web layer) εντός των ορίων του

**Συνοπτικά:** Ο κάθε component πρέπει να περιέχει 'επίπεδα' (layers) - ξεχωριστές οντότητες για το διαδίκτυο(web), την επιχειρησιακή λογική (business logic) και την πρόσβαση στα δεδομένα (data access). Αυτό όχι μόνο δημιουργεί καθαρό διαχωρισμό των λειτουργιών, αλλά επίσης διευκολύνει σημαντικά την διαδικασία ελέγχου (mocking and testing) της εφαρμογής. Αν και αυτό είναι διαδεδομένη πρακτική, οι προγραμματιστές API τείνουν να αναμιγνύουν τα επίπεδα, μεταβιβάζοντας οντότητες του επιπέδου διαδικτύου (π.χ Express req, res) στο επίπεδο επιχειρησιακής λογικής. Αυτό καθιστα την εφαρμογή εξαρτόμενη και προσβάσιμη μόνο από συγκεκριμένα frameworks.

**Διαφορετικά:** Η εφαρμογή που αναμιγνύει τo επίπεδο διαδικτύου με άλλα επίπεδα στην εφαρμογή δεν μπορεί να είναι προσβάσιμη από τον κώδικα που ελέγχει την εφαρμογή (testing code), CRON jobs, triggers από message queues κλπ.

🔗 [**Διαβάστε Περισσότερα: Διαχωρείστε την εφαρμογή σας σε επίπεδα**](/sections/projectstructre/createlayers.md)

<br/><br/>

## ![✔] 1.3 Διασπάστε την κοινή λειτουργικότητα (utilities) σε npm πακέτα(npm packages)

**Συνοπτικά:** Σε μεγάλα έργα λογισμικού με χιλιάδες γραμμές κώδικα η λειτουργικότητα που χρησιμοποιείται ήδη σε διαφορετικά επίπεδα της εφαρμογής όπως οι loggers, η κρυπτογράφιση κλπ, πρέπει να διασπαστεί σε ιδιωτικά npm packages. Αυτό βοηθάει στον διαμοιρασμό αυτής, μεταξύ διαφορετικών σημείων στον κώδικα αλλά και στην χρησιμοποίηση της σε διαφορετικά έργα.

**Διαφορετικά:** Θα χρειαστείτε πολύ κόπο και χρόνο στη συντήρηση του κώδικα και στη διαχείριση της διαδικασίας παραγωγής .

🔗 [**Διαβάστε Περισσότερα: Διαχωρισμός με βάση τα χαρακτηριστικά της εφαρμογής**](/sections/projectstructre/wraputilities.md)

<br/><br/>

## ![✔] 1.4 Διαχωρίστε το Express 'app' και τον Express 'server'

**Συνοπτικά:** Αποφύγετε την κακή συνήθεια υλοποίησης ολόκληρου του  [Express](https://expressjs.com/) app σε ένα μόνο τεράστιο αρχείο - διαχωρίστε την υλοποίηση του 'Express' σε τουλάχιστον 2 αρχεία: Την υλοποίηση του API (app.js) και την υλοποίηση διαδικτύου (WWW). Για ακόμα καλύτερο διαχωρισμό, διασπάστε την υλοποίηση του API εντός των components.

**Διαφορετικά:** Το API σας θα είναι διαθέσιμο για δοκιμή (testing) μόνο μέσω HTTP calls (πιο αργή και πολύ πιο δύσκολη δημιουργία coverage reports). Επιπλέον δεν θα είναι εύκολη η συντήριση χιλιάδων γραμμών κώδικα σε ένα μόνο αρχείο.

🔗 [**Διαβάστε Περισσότερα: Διαχωρίστε το Express 'app' και τον Express 'server''**](/sections/projectstructre/separateexpress.md)

<br/><br/>

## ![✔] 1.5 Χρησιμοποιήστε ασφαλής, ιεραρχημένες και μη εξαρτόμενες από το περιβάλλον υλοποίησης παραμέτρους

**Συνοπτικά:** H τέλεια διαμόρφωση παραμέτρων (configuration setup) θα πρέπεινα διασφαλίζει ότι (α) οι παράμετροι θα είναι προσβάσιμοι από αρχεία ΚΑΙ από μεταβλητες περιβάλλοντος υλοποίησης (environment variable) (β) οι κρυφοί παράμετροι θα πρέπει να μήν είναι αναγνώσιμοι από κώδικα που έχει ανέβει σε κάποιο repository (commited code) (c) οι παράμετροι θα πρέπει να είναι ιεραρχημένοι για να μπορούν να είναι πιο εύκολα προσβάσιμοι. Υπάρχουν βιβλιοθήκες που μπορούν να βοηθήσουν με τα παραπάνω όπως οι [rc](https://www.npmjs.com/package/rc), [nconf](https://www.npmjs.com/package/nconf), [config](https://www.npmjs.com/package/config), και [convict](https://www.npmjs.com/package/convict).

**Διαφορετικά:** Η αποτυχία ικανοποίησης των παραπάνω προϋποθέσεων έχει ως αποτέλεσμα την καθυστέριση της παραγωγής κώδικα και της ομάδας devops.
🔗 [**Διαβάστε Περισσότερα: Βέλτιστες πρακτικες παραμετροποίησης**](/sections/projectstructre/configguide.md)

<br/><br/><br/>

<p align="right"><a href="#table-of-contents">⬆ Return to top</a></p>

# `2. Error Handling Practices`

## ![✔] 2.1 Use Async-Await or promises for async error handling

**Συνοπτικά:** Handling async errors in callback style is probably the fastest way to hell (a.k.a the pyramid of doom). The best gift you can give to your code is using a reputable promise library or async-await instead which enables a much more compact and familiar code syntax like try-catch

**Διαφορετικά:** Node.js callback style, function(err, response), is a promising way to un-maintainable code due to the mix of error handling with casual code, excessive nesting, and awkward coding patterns

🔗 [**Διαβάστε Περισσότερα: avoiding callbacks**](/sections/errorhandling/asyncerrorhandling.md)

<br/><br/>

## ![✔] 2.2 Use only the built-in Error object

**Συνοπτικά:** Many throw errors as a string or as some custom type – this complicates the error handling logic and the interoperability between modules. Whether you reject a promise, throw an exception or emit an error – using only the built-in Error object (or an object that extends the built-in Error object) will increase uniformity and prevent loss of information

**Διαφορετικά:** When invoking some component, being uncertain which type of errors come in return – it makes proper error handling much harder. Even worse, using custom types to describe errors might lead to loss of critical error information like the stack trace!

🔗 [**Διαβάστε Περισσότερα: using the built-in error object**](/sections/errorhandling/useonlythebuiltinerror.md)

<br/><br/>

## ![✔] 2.3 Distinguish operational vs programmer errors

**Συνοπτικά:** Operational errors (e.g. API received an invalid input) refer to known cases where the error impact is fully understood and can be handled thoughtfully. On the other hand, programmer error (e.g. trying to read undefined variable) refers to unknown code failures that dictate to gracefully restart the application

**Διαφορετικά:** You may always restart the application when an error appears, but why let ~5000 online users down because of a minor, predicted, operational error? the opposite is also not ideal – keeping the application up when an unknown issue (programmer error) occurred might lead to an unpredicted behavior. Differentiating the two allows acting tactfully and applying a balanced approach based on the given context

🔗 [**Διαβάστε Περισσότερα: operational vs programmer error**](/sections/errorhandling/operationalvsprogrammererror.md)

<br/><br/>

## ![✔] 2.4 Handle errors centrally, not within a middleware

**Συνοπτικά:** Error handling logic such as mail to admin and logging should be encapsulated in a dedicated and centralized object that all endpoints (e.g. Express middleware, cron jobs, unit-testing) call when an error comes in

**Διαφορετικά:** Not handling errors within a single place will lead to code duplication and probably to improperly handled errors

🔗 [**Διαβάστε Περισσότερα: handling errors in a centralized place**](/sections/errorhandling/centralizedhandling.md)

<br/><br/>

## ![✔] 2.5 Document API errors using Swagger or GraphQL

**Συνοπτικά:** Let your API callers know which errors might come in return so they can handle these thoughtfully without crashing. For RESTful APIs, this is usually done with documentation frameworks like Swagger. If you're using GraphQL, you can utilize your schema and comments as well.

**Διαφορετικά:** An API client might decide to crash and restart only because it received back an error it couldn’t understand. Note: the caller of your API might be you (very typical in a microservice environment)

🔗 [**Διαβάστε Περισσότερα: documenting API errors in Swagger or GraphQL**](/sections/errorhandling/documentingusingswagger.md)

<br/><br/>

## ![✔] 2.6 Exit the process gracefully when a stranger comes to town

**Συνοπτικά:** When an unknown error occurs (a developer error, see best practice 2.3) - there is uncertainty about the application healthiness. A common practice suggests restarting the process carefully using a process management tool like [Forever](https://www.npmjs.com/package/forever) or [PM2](http://pm2.keymetrics.io/)

**Διαφορετικά:** When an unfamiliar exception occurs, some object might be in a faulty state (e.g. an event emitter which is used globally and not firing events anymore due to some internal failure) and all future requests might fail or behave crazily

🔗 [**Διαβάστε Περισσότερα: shutting the process**](/sections/errorhandling/shuttingtheprocess.md)

<br/><br/>

## ![✔] 2.7 Use a mature logger to increase error visibility

**Συνοπτικά:** A set of mature logging tools like [Pino](https://github.com/pinojs/pino) or [Log4js](https://www.npmjs.com/package/log4js), will speed-up error discovery and understanding. So forget about console.log

**Διαφορετικά:** Skimming through console.logs or manually through messy text file without querying tools or a decent log viewer might keep you busy at work until late

🔗 [**Διαβάστε Περισσότερα: using a mature logger**](/sections/errorhandling/usematurelogger.md)

<br/><br/>

## ![✔] 2.8 Test error flows using your favorite test framework

**Συνοπτικά:** Whether professional automated QA or plain manual developer testing – Ensure that your code not only satisfies positive scenarios but also handles and returns the right errors. Testing frameworks like Mocha & Chai can handle this easily (see code examples within the "Gist popup")

**Διαφορετικά:** Without testing, whether automatically or manually, you can’t rely on your code to return the right errors. Without meaningful errors – there’s no error handling

🔗 [**Διαβάστε Περισσότερα: testing error flows**](/sections/errorhandling/testingerrorflows.md)

<br/><br/>

## ![✔] 2.9 Discover errors and downtime using APM products

**Συνοπτικά:** Monitoring and performance products (a.k.a APM) proactively gauge your codebase or API so they can automagically highlight errors, crashes and slow parts that you were missing

**Διαφορετικά:** You might spend great effort on measuring API performance and downtimes, probably you’ll never be aware which are your slowest code parts under real-world scenario and how these affect the UX

🔗 [**Διαβάστε Περισσότερα: using APM products**](/sections/errorhandling/apmproducts.md)

<br/><br/>

## ![✔] 2.10 Catch unhandled promise rejections

**Συνοπτικά:** Any exception thrown within a promise will get swallowed and discarded unless a developer didn’t forget to explicitly handle. Even if your code is subscribed to `process.uncaughtException`! Overcome this by registering to the event `process.unhandledRejection`

**Διαφορετικά:** Your errors will get swallowed and leave no trace. Nothing to worry about

🔗 [**Διαβάστε Περισσότερα: catching unhandled promise rejection**](/sections/errorhandling/catchunhandledpromiserejection.md)

<br/><br/>

## ![✔] 2.11 Fail fast, validate arguments using a dedicated library

**Συνοπτικά:** Assert API input to avoid nasty bugs that are much harder to track later. The validation code is usually tedious unless you are using a very cool helper library like [ajv](https://www.npmjs.com/package/ajv) and [Joi](https://www.npmjs.com/package/joi)

**Διαφορετικά:** Consider this – your function expects a numeric argument “Discount” which the caller forgets to pass, later on, your code checks if Discount!=0 (amount of allowed discount is greater than zero), then it will allow the user to enjoy a discount. OMG, what a nasty bug. Can you see it?

🔗 [**Διαβάστε Περισσότερα: failing fast**](/sections/errorhandling/failfast.md)

<br/><br/><br/>

<p align="right"><a href="#table-of-contents">⬆ Return to top</a></p>

# `3. Code Style Practices`

## ![✔] 3.1 Use ESLint

**Συνοπτικά:** [ESLint](https://eslint.org) is the de-facto standard for checking possible code errors and fixing code style, not only to identify nitty-gritty spacing issues but also to detect serious code anti-patterns like developers throwing errors without classification. Though ESLint can automatically fix code styles, other tools like [prettier](https://www.npmjs.com/package/prettier) and [beautify](https://www.npmjs.com/package/js-beautify) are more powerful in formatting the fix and work in conjunction with ESLint

**Διαφορετικά:** Developers will focus on tedious spacing and line-width concerns and time might be wasted overthinking the project's code style

🔗 [**Διαβάστε Περισσότερα: Using ESLint and Prettier**](/sections/codestylepractices/eslint_prettier.md)

<br/><br/>

## ![✔] 3.2 Node.js specific plugins

**Συνοπτικά:** On top of ESLint standard rules that cover vanilla JavaScript, add Node.js specific plugins like [eslint-plugin-node](https://www.npmjs.com/package/eslint-plugin-node), [eslint-plugin-mocha](https://www.npmjs.com/package/eslint-plugin-mocha) and [eslint-plugin-node-security](https://www.npmjs.com/package/eslint-plugin-security)

**Διαφορετικά:** Many faulty Node.js code patterns might escape under the radar. For example, developers might require(variableAsPath) files with a variable given as path which allows attackers to execute any JS script. Node.js linters can detect such patterns and complain early

<br/><br/>

## ![✔] 3.3 Start a Codeblock's Curly Braces on the Same Line

**Συνοπτικά:** The opening curly braces of a code block should be on the same line as the opening statement

### Code Example

```javascript
// Do
function someFunction() {
  // code block
}

// Avoid
function someFunction()
{
  // code block
}
```

**Διαφορετικά:** Deferring from this best practice might lead to unexpected results, as seen in the StackOverflow thread below:

🔗 [**Διαβάστε Περισσότερα:** "Why do results vary based on curly brace placement?" (StackOverflow)](https://stackoverflow.com/questions/3641519/why-does-a-results-vary-based-on-curly-brace-placement)

<br/><br/>

## ![✔] 3.4 Separate your statements properly

No matter if you use semicolons or not to separate your statements, knowing the common pitfalls of improper linebreaks or automatic semicolon insertion, will help you to eliminate regular syntax errors.

**Συνοπτικά:** Use ESLint to gain awareness about separation concerns. [Prettier](https://prettier.io/) or [Standardjs](https://standardjs.com/) can automatically resolve these issues.

**Διαφορετικά:** As seen in the previous section, JavaScript's interpreter automatically adds a semicolon at the end of a statement if there isn't one, or considers a statement as not ended where it should, which might lead to some undesired results. You can use assignments and avoid using immediate invoked function expressions to prevent most of unexpected errors.

### Code example

```javascript
// Do
function doThing() {
    // ...
}

doThing()

// Do

const items = [1, 2, 3]
items.forEach(console.log)

// Avoid — throws exception
const m = new Map()
const a = [1,2,3]
[...m.values()].forEach(console.log)
> [...m.values()].forEach(console.log)
>  ^^^
> SyntaxError: Unexpected token ...

// Avoid — throws exception
const count = 2 // it tries to run 2(), but 2 is not a function
(function doSomething() {
  // do something amazing
}())
// put a semicolon before the immediate invoked function, after the const definition, save the return value of the anonymous function to a variable or avoid IIFEs alltogether
```

🔗 [**Διαβάστε Περισσότερα:** "Semi ESLint rule"](https://eslint.org/docs/rules/semi)
🔗 [**Διαβάστε Περισσότερα:** "No unexpected multiline ESLint rule"](https://eslint.org/docs/rules/no-unexpected-multiline)

<br/><br/>

## ![✔] 3.5 Name your functions

**Συνοπτικά:** Name all functions, including closures and callbacks. Avoid anonymous functions. This is especially useful when profiling a node app. Naming all functions will allow you to easily understand what you're looking at when checking a memory snapshot

**Διαφορετικά:** Debugging production issues using a core dump (memory snapshot) might become challenging as you notice significant memory consumption from anonymous functions

<br/><br/>

## ![✔] 3.6 Use naming conventions for variables, constants, functions and classes

**Συνοπτικά:** Use **_lowerCamelCase_** when naming constants, variables and functions and **_UpperCamelCase_** (capital first letter as well) when naming classes. This will help you to easily distinguish between plain variables/functions, and classes that require instantiation. Use descriptive names, but try to keep them short

**Διαφορετικά:** Javascript is the only language in the world which allows invoking a constructor ("Class") directly without instantiating it first. Consequently, Classes and function-constructors are differentiated by starting with UpperCamelCase

### 3.6 Code Example

```javascript
// for class name we use UpperCamelCase
class SomeClassExample {}

// for const names we use the const keyword and lowerCamelCase
const config = {
  key: "value"
};

// for variables and functions names we use lowerCamelCase
let someVariableExample = "value";
function doSomething() {}
```

<br/><br/>

## ![✔] 3.7 Prefer const over let. Ditch the var

**Συνοπτικά:** Using `const` means that once a variable is assigned, it cannot be reassigned. Preferring `const` will help you to not be tempted to use the same variable for different uses, and make your code clearer. If a variable needs to be reassigned, in a for loop, for example, use `let` to declare it. Another important aspect of `let` is that a variable declared using it is only available in the block scope in which it was defined. `var` is function scoped, not block scoped, and [shouldn't be used in ES6](https://hackernoon.com/why-you-shouldnt-use-var-anymore-f109a58b9b70) now that you have `const` and `let` at your disposal

**Διαφορετικά:** Debugging becomes way more cumbersome when following a variable that frequently changes

🔗 [**Διαβάστε Περισσότερα: JavaScript ES6+: var, let, or const?** ](https://medium.com/javascript-scene/javascript-es6-var-let-or-const-ba58b8dcde75)

<br/><br/>

## ![✔] 3.8 Require modules first, not inside functions

**Συνοπτικά:** Require modules at the beginning of each file, before and outside of any functions. This simple best practice will not only help you easily and quickly tell the dependencies of a file right at the top but also avoids a couple of potential problems

**Διαφορετικά:** Requires are run synchronously by Node.js. If they are called from within a function, it may block other requests from being handled at a more critical time. Also, if a required module or any of its own dependencies throw an error and crash the server, it is best to find out about it as soon as possible, which might not be the case if that module is required from within a function

<br/><br/>

## ![✔] 3.9 Require modules by folders, opposed to the files directly

**Συνοπτικά:** When developing a module/library in a folder, place an index.js file that exposes the module's internals so every consumer will pass through it. This serves as an 'interface' to your module and eases future changes without breaking the contract

**Διαφορετικά:** Changing the internal structure of files or the signature may break the interface with clients

### 3.9 Code example

```javascript
// Do
module.exports.SMSProvider = require("./SMSProvider");
module.exports.SMSNumberResolver = require("./SMSNumberResolver");

// Avoid
module.exports.SMSProvider = require("./SMSProvider/SMSProvider.js");
module.exports.SMSNumberResolver = require("./SMSNumberResolver/SMSNumberResolver.js");
```

<br/><br/>

## ![✔] 3.10 Use the `===` operator

**Συνοπτικά:** Prefer the strict equality operator `===` over the weaker abstract equality operator `==`. `==` will compare two variables after converting them to a common type. There is no type conversion in `===`, and both variables must be of the same type to be equal

**Διαφορετικά:** Unequal variables might return true when compared with the `==` operator

### 3.10 Code example

```javascript
"" == "0"; // false
0 == ""; // true
0 == "0"; // true

false == "false"; // false
false == "0"; // true

false == undefined; // false
false == null; // false
null == undefined; // true

" \t\r\n " == 0; // true
```

All statements above will return false if used with `===`

<br/><br/>

## ![✔] 3.11 Use Async Await, avoid callbacks

**Συνοπτικά:** Node 8 LTS now has full support for Async-await. This is a new way of dealing with asynchronous code which supersedes callbacks and promises. Async-await is non-blocking, and it makes asynchronous code look synchronous. The best gift you can give to your code is using async-await which provides a much more compact and familiar code syntax like try-catch

**Διαφορετικά:** Handling async errors in callback style is probably the fastest way to hell - this style forces to check errors all over, deal with awkward code nesting and makes it difficult to reason about the code flow

🔗[**Διαβάστε Περισσότερα:** Guide to async await 1.0](https://github.com/yortus/asyncawait)

<br/><br/>

## ![✔] 3.12 Use arrow function expressions (=>)

**Συνοπτικά:** Though it's recommended to use async-await and avoid function parameters when dealing with older APIs that accept promises or callbacks - arrow functions make the code structure more compact and keep the lexical context of the root function (i.e. `this`)

**Διαφορετικά:** Longer code (in ES5 functions) is more prone to bugs and cumbersome to read

🔗 [**Διαβάστε Περισσότερα: It’s Time to Embrace Arrow Functions**](https://medium.com/javascript-scene/familiarity-bias-is-holding-you-back-its-time-to-embrace-arrow-functions-3d37e1a9bb75)

<br/><br/><br/>

<p align="right"><a href="#table-of-contents">⬆ Return to top</a></p>

# `4. Testing And Overall Quality Practices`

## ![✔] 4.1 At the very least, write API (component) testing

**Συνοπτικά:** Most projects just don't have any automated testing due to short timetables or often the 'testing project' ran out of control and was abandoned. For that reason, prioritize and start with API testing which is the easiest way to write and provides more coverage than unit testing (you may even craft API tests without code using tools like [Postman](https://www.getpostman.com/). Afterward, should you have more resources and time, continue with advanced test types like unit testing, DB testing, performance testing, etc

**Διαφορετικά:** You may spend long days on writing unit tests to find out that you got only 20% system coverage

<br/><br/>

## ![✔] 4.2 Include 3 parts in each test name

**Συνοπτικά:** Make the test speak at the requirements level so it's self explanatory also to QA engineers and developers who are not familiar with the code internals. State in the test name what is being tested (unit under test), under what circumstances and what is the expected result

**Διαφορετικά:** A deployment just failed, a test named “Add product” failed. Does this tell you what exactly is malfunctioning?

🔗 [**Διαβάστε Περισσότερα: Include 3 parts in each test name**](/sections/testingandquality/3-parts-in-name.md)

<br/><br/>

## ![✔] 4.3 Structure tests by the AAA pattern

**Συνοπτικά:** Structure your tests with 3 well-separated sections: Arrange, Act & Assert (AAA). The first part includes the test setup, then the execution of the unit under test and finally the assertion phase. Following this structure guarantees that the reader spends no brain CPU on understanding the test plan

**Διαφορετικά:** Not only you spend long daily hours on understanding the main code, now also what should have been the simple part of the day (testing) stretches your brain

🔗 [**Διαβάστε Περισσότερα: Structure tests by the AAA pattern**](/sections/testingandquality/aaa.md)

<br/><br/>

## ![✔] 4.4 Detect code issues with a linter

**Συνοπτικά:** Use a code linter to check basic quality and detect anti-patterns early. Run it before any test and add it as a pre-commit git-hook to minimize the time needed to review and correct any issue. Also check [Section 3](#3-code-style-practices) on Code Style Practices

**Διαφορετικά:** You may let pass some anti-pattern and possible vulnerable code to your production environment.

<br/><br/>

## ![✔] 4.5 Avoid global test fixtures and seeds, add data per-test

**Συνοπτικά:** To prevent tests coupling and easily reason about the test flow, each test should add and act on its own set of DB rows. Whenever a test needs to pull or assume the existence of some DB data - it must explicitly add that data and avoid mutating any other records

**Διαφορετικά:** Consider a scenario where deployment is aborted due to failing tests, team is now going to spend precious investigation time that ends in a sad conclusion: the system works well, the tests however interfere with each other and break the build

🔗 [**Διαβάστε Περισσότερα: Avoid global test fixtures**](/sections/testingandquality/avoid-global-test-fixture.md)

<br/><br/>

## ![✔] 4.6 Constantly inspect for vulnerable dependencies

**Συνοπτικά:** Even the most reputable dependencies such as Express have known vulnerabilities. This can get easily tamed using community and commercial tools such as 🔗 [npm audit](https://docs.npmjs.com/cli/audit) and 🔗 [snyk.io](https://snyk.io) that can be invoked from your CI on every build

**Διαφορετικά:** Keeping your code clean from vulnerabilities without dedicated tools will require to constantly follow online publications about new threats. Quite tedious

<br/><br/>

## ![✔] 4.7 Tag your tests

**Συνοπτικά:** Different tests must run on different scenarios: quick smoke, IO-less, tests should run when a developer saves or commits a file, full end-to-end tests usually run when a new pull request is submitted, etc. This can be achieved by tagging tests with keywords like #cold #api #sanity so you can grep with your testing harness and invoke the desired subset. For example, this is how you would invoke only the sanity test group with [Mocha](https://mochajs.org/): mocha --grep 'sanity'

**Διαφορετικά:** Running all the tests, including tests that perform dozens of DB queries, any time a developer makes a small change can be extremely slow and keeps developers away from running tests

<br/><br/>

## ![✔] 4.8 Check your test coverage, it helps to identify wrong test patterns

**Συνοπτικά:** Code coverage tools like [Istanbul](https://github.com/istanbuljs/istanbuljs)/[NYC](https://github.com/istanbuljs/nyc) are great for 3 reasons: it comes for free (no effort is required to benefit this reports), it helps to identify a decrease in testing coverage, and last but not least it highlights testing mismatches: by looking at colored code coverage reports you may notice, for example, code areas that are never tested like catch clauses (meaning that tests only invoke the happy paths and not how the app behaves on errors). Set it to fail builds if the coverage falls under a certain threshold

**Διαφορετικά:** There won't be any automated metric telling you when a large portion of your code is not covered by testing

<br/><br/>

## ![✔] 4.9 Inspect for outdated packages

**Συνοπτικά:** Use your preferred tool (e.g. 'npm outdated' or [npm-check-updates](https://www.npmjs.com/package/npm-check-updates) to detect installed packages which are outdated, inject this check into your CI pipeline and even make a build fail in a severe scenario. For example, a severe scenario might be when an installed package is 5 patch commits behind (e.g. local version is 1.3.1 and repository version is 1.3.8) or it is tagged as deprecated by its author - kill the build and prevent deploying this version

**Διαφορετικά:** Your production will run packages that have been explicitly tagged by their author as risky

<br/><br/>

## ![✔] 4.10 Use production-like environment for e2e testing

**Συνοπτικά:** End to end (e2e) testing which includes live data used to be the weakest link of the CI process as it depends on multiple heavy services like DB. Use an environment which is as close to your real production environment as possible like a-continue (Missed -continue here, needs content. Judging by the **Διαφορετικά** clause, this should mention docker-compose)

**Διαφορετικά:** Without docker-compose, teams must maintain a testing DB for each testing environment including developers' machines, keep all those DBs in sync so test results won't vary across environments

<br/><br/>

## ![✔] 4.11 Refactor regularly using static analysis tools

**Συνοπτικά:** Using static analysis tools helps by giving objective ways to improve code quality and keeps your code maintainable. You can add static analysis tools to your CI build to fail when it finds code smells. Its main selling points over plain linting are the ability to inspect quality in the context of multiple files (e.g. detect duplications), perform advanced analysis (e.g. code complexity) and follow the history and progress of code issues. Two examples of tools you can use are [Sonarqube](https://www.sonarqube.org/) (2,600+ [stars](https://github.com/SonarSource/sonarqube)) and [Code Climate](https://codeclimate.com/) (1,500+ [stars](https://github.com/codeclimate/codeclimate)).

**Διαφορετικά:** With poor code quality, bugs and performance will always be an issue that no shiny new library or state of the art features can fix

🔗 [**Διαβάστε Περισσότερα: Refactoring!**](/sections/testingandquality/refactoring.md)

<br/><br/>

## ![✔] 4.12 Carefully choose your CI platform (Jenkins vs CircleCI vs Travis vs Rest of the world)

**Συνοπτικά:** Your continuous integration platform (CICD) will host all the quality tools (e.g test, lint) so it should come with a vibrant ecosystem of plugins. [Jenkins](https://jenkins.io/) used to be the default for many projects as it has the biggest community along with a very powerful platform at the price of complex setup that demands a steep learning curve. Nowadays, it has become much easier to set up a CI solution using SaaS tools like [CircleCI](https://circleci.com) and others. These tools allow crafting a flexible CI pipeline without the burden of managing the whole infrastructure. Eventually, it's a trade-off between robustness and speed - choose your side carefully

**Διαφορετικά:** Choosing some niche vendor might get you blocked once you need some advanced customization. On the other hand, going with Jenkins might burn precious time on infrastructure setup

🔗 [**Διαβάστε Περισσότερα: Choosing CI platform**](/sections/testingandquality/citools.md)

## ![✔] 4.13 Test your middlewares in isolation

**Συνοπτικά:** When a middleware holds some immense logic that spans many request, it worth testing it in isolation without waking up the entire web framework. This can be easily achieved by stubbing and spying on the {req, res, next} objects

**Διαφορετικά:** A bug in Express middleware === a bug in all or most requests

🔗 [**Διαβάστε Περισσότερα: Test middlewares in isolation**](/sections/testingandquality/test-middlewares.md)

<br/><br/><br/>

<p align="right"><a href="#table-of-contents">⬆ Return to top</a></p>

# `5. Going To Production Practices`

## ![✔] 5.1. Monitoring

**Συνοπτικά:** Monitoring is a game of finding out issues before customers do – obviously this should be assigned unprecedented importance. The market is overwhelmed with offers thus consider starting with defining the basic metrics you must follow (my suggestions inside), then go over additional fancy features and choose the solution that ticks all boxes. Click ‘The Gist’ below for an overview of the solutions

**Διαφορετικά:** Failure === disappointed customers. Simple

🔗 [**Διαβάστε Περισσότερα: Monitoring!**](/sections/production/monitoring.md)

<br/><br/>

## ![✔] 5.2. Increase transparency using smart logging

**Συνοπτικά:** Logs can be a dumb warehouse of debug statements or the enabler of a beautiful dashboard that tells the story of your app. Plan your logging platform from day 1: how logs are collected, stored and analyzed to ensure that the desired information (e.g. error rate, following an entire transaction through services and servers, etc) can really be extracted

**Διαφορετικά:** You end up with a black box that is hard to reason about, then you start re-writing all logging statements to add additional information

🔗 [**Διαβάστε Περισσότερα: Increase transparency using smart logging**](/sections/production/smartlogging.md)

<br/><br/>

## ![✔] 5.3. Delegate anything possible (e.g. gzip, SSL) to a reverse proxy

**Συνοπτικά:** Node is awfully bad at doing CPU intensive tasks like gzipping, SSL termination, etc. You should use ‘real’ middleware services like nginx, HAproxy or cloud vendor services instead

**Διαφορετικά:** Your poor single thread will stay busy doing infrastructural tasks instead of dealing with your application core and performance will degrade accordingly

🔗 [**Διαβάστε Περισσότερα: Delegate anything possible (e.g. gzip, SSL) to a reverse proxy**](/sections/production/delegatetoproxy.md)

<br/><br/>

## ![✔] 5.4. Lock dependencies

**Συνοπτικά:** Your code must be identical across all environments, but amazingly npm lets dependencies drift across environments by default – when you install packages at various environments it tries to fetch packages’ latest patch version. Overcome this by using npm config files, .npmrc, that tell each environment to save the exact (not the latest) version of each package. Alternatively, for finer grained control use `npm shrinkwrap`. \*Update: as of NPM5, dependencies are locked by default. The new package manager in town, Yarn, also got us covered by default

**Διαφορετικά:** QA will thoroughly test the code and approve a version that will behave differently in production. Even worse, different servers in the same production cluster might run different code

🔗 [**Διαβάστε Περισσότερα: Lock dependencies**](/sections/production/lockdependencies.md)

<br/><br/>

## ![✔] 5.5. Guard process uptime using the right tool

**Συνοπτικά:** The process must go on and get restarted upon failures. For simple scenarios, process management tools like PM2 might be enough but in today's ‘dockerized’ world, cluster management tools should be considered as well

**Διαφορετικά:** Running dozens of instances without a clear strategy and too many tools together (cluster management, docker, PM2) might lead to DevOps chaos

🔗 [**Διαβάστε Περισσότερα: Guard process uptime using the right tool**](/sections/production/guardprocess.md)

<br/><br/>

## ![✔] 5.6. Utilize all CPU cores

**Συνοπτικά:** At its basic form, a Node app runs on a single CPU core while all others are left idling. It’s your duty to replicate the Node process and utilize all CPUs – For small-medium apps you may use Node Cluster or PM2. For a larger app consider replicating the process using some Docker cluster (e.g. K8S, ECS) or deployment scripts that are based on Linux init system (e.g. systemd)

**Διαφορετικά:** Your app will likely utilize only 25% of its available resources(!) or even less. Note that a typical server has 4 CPU cores or more, naive deployment of Node.js utilizes only 1 (even using PaaS services like AWS beanstalk!)

🔗 [**Διαβάστε Περισσότερα: Utilize all CPU cores**](/sections/production/utilizecpu.md)

<br/><br/>

## ![✔] 5.7. Create a ‘maintenance endpoint’

**Συνοπτικά:** Expose a set of system-related information, like memory usage and REPL, etc in a secured API. Although it’s highly recommended to rely on standard and battle-tests tools, some valuable information and operations are easier done using code

**Διαφορετικά:** You’ll find that you’re performing many “diagnostic deploys” – shipping code to production only to extract some information for diagnostic purposes

🔗 [**Διαβάστε Περισσότερα: Create a ‘maintenance endpoint’**](/sections/production/createmaintenanceendpoint.md)

<br/><br/>

## ![✔] 5.8. Discover errors and downtime using APM products

**Συνοπτικά:** Application monitoring and performance products (a.k.a APM) proactively gauge codebase and API so they can auto-magically go beyond traditional monitoring and measure the overall user-experience across services and tiers. For example, some APM products can highlight a transaction that loads too slow on the end-users side while suggesting the root cause

**Διαφορετικά:** You might spend great effort on measuring API performance and downtimes, probably you’ll never be aware which is your slowest code parts under real-world scenario and how these affect the UX

🔗 [**Διαβάστε Περισσότερα: Discover errors and downtime using APM products**](/sections/production/apmproducts.md)

<br/><br/>

## ![✔] 5.9. Make your code production-ready

**Συνοπτικά:** Code with the end in mind, plan for production from day 1. This sounds a bit vague so I’ve compiled a few development tips that are closely related to production maintenance (click Gist below)

**Διαφορετικά:** A world champion IT/DevOps guy won’t save a system that is badly written

🔗 [**Διαβάστε Περισσότερα: Make your code production-ready**](/sections/production/productioncode.md)

<br/><br/>

## ![✔] 5.10. Measure and guard the memory usage

**Συνοπτικά:** Node.js has controversial relationships with memory: the v8 engine has soft limits on memory usage (1.4GB) and there are known paths to leak memory in Node’s code – thus watching Node’s process memory is a must. In small apps, you may gauge memory periodically using shell commands but in medium-large apps consider baking your memory watch into a robust monitoring system

**Διαφορετικά:** Your process memory might leak a hundred megabytes a day like how it happened at [Walmart](https://www.joyent.com/blog/walmart-node-js-memory-leak)

🔗 [**Διαβάστε Περισσότερα: Measure and guard the memory usage**](/sections/production/measurememory.md)

<br/><br/>

## ![✔] 5.11. Get your frontend assets out of Node

**Συνοπτικά:** Serve frontend content using dedicated middleware (nginx, S3, CDN) because Node performance really gets hurt when dealing with many static files due to its single-threaded model

**Διαφορετικά:** Your single Node thread will be busy streaming hundreds of html/images/angular/react files instead of allocating all its resources for the task it was born for – serving dynamic content

🔗 [**Διαβάστε Περισσότερα: Get your frontend assets out of Node**](/sections/production/frontendout.md)

<br/><br/>

## ![✔] 5.12. Be stateless, kill your servers almost every day

**Συνοπτικά:** Store any type of data (e.g. user sessions, cache, uploaded files) within external data stores. Consider ‘killing’ your servers periodically or use ‘serverless’ platform (e.g. AWS Lambda) that explicitly enforces a stateless behavior

**Διαφορετικά:** Failure at a given server will result in application downtime instead of just killing a faulty machine. Moreover, scaling-out elasticity will get more challenging due to the reliance on a specific server

🔗 [**Διαβάστε Περισσότερα: Be stateless, kill your Servers almost every day**](/sections/production/bestateless.md)

<br/><br/>

## ![✔] 5.13. Use tools that automatically detect vulnerabilities

**Συνοπτικά:** Even the most reputable dependencies such as Express have known vulnerabilities (from time to time) that can put a system at risk. This can be easily tamed using community and commercial tools that constantly check for vulnerabilities and warn (locally or at GitHub), some can even patch them immediately

**Διαφορετικά:** Keeping your code clean from vulnerabilities without dedicated tools will require you to constantly follow online publications about new threats. Quite tedious

🔗 [**Διαβάστε Περισσότερα: Use tools that automatically detect vulnerabilities**](/sections/production/detectvulnerabilities.md)

<br/><br/>

## ![✔] 5.14. Assign a transaction id to each log statement

**Συνοπτικά:** Assign the same identifier, transaction-id: {some value}, to each log entry within a single request. Then when inspecting errors in logs, easily conclude what happened before and after. Unfortunately, this is not easy to achieve in Node due to its async nature, see code examples inside

**Διαφορετικά:** Looking at a production error log without the context – what happened before – makes it much harder and slower to reason about the issue

🔗 [**Διαβάστε Περισσότερα: Assign ‘TransactionId’ to each log statement**](/sections/production/assigntransactionid.md)

<br/><br/>

## ![✔] 5.15. Set NODE_ENV=production

**Συνοπτικά:** Set the environment variable NODE_ENV to ‘production’ or ‘development’ to flag whether production optimizations should get activated – many npm packages determine the current environment and optimize their code for production

**Διαφορετικά:** Omitting this simple property might greatly degrade performance. For example, when using Express for server-side rendering omitting `NODE_ENV` makes it slower by a factor of three!

🔗 [**Διαβάστε Περισσότερα: Set NODE_ENV=production**](/sections/production/setnodeenv.md)

<br/><br/>

## ![✔] 5.16. Design automated, atomic and zero-downtime deployments

**Συνοπτικά:** Research shows that teams who perform many deployments lower the probability of severe production issues. Fast and automated deployments that don’t require risky manual steps and service downtime significantly improve the deployment process. You should probably achieve this using Docker combined with CI tools as they became the industry standard for streamlined deployment

**Διαφορετικά:** Long deployments -> production downtime & human-related error -> team unconfident in making deployment -> fewer deployments and features

<br/><br/>

## ![✔] 5.17. Use an LTS release of Node.js

**Συνοπτικά:** Ensure you are using an LTS version of Node.js to receive critical bug fixes, security updates and performance improvements

**Διαφορετικά:** Newly discovered bugs or vulnerabilities could be used to exploit an application running in production, and your application may become unsupported by various modules and harder to maintain

🔗 [**Διαβάστε Περισσότερα: Use an LTS release of Node.js**](/sections/production/LTSrelease.md)

<br/><br/>

## ![✔] 5.18. Don't route logs within the app

**Συνοπτικά:** Log destinations should not be hard-coded by developers within the application code, but instead should be defined by the execution environment the application runs in. Developers should write logs to `stdout` using a logger utility and then let the execution environment (container, server, etc.) pipe the `stdout` stream to the appropriate destination (i.e. Splunk, Graylog, ElasticSearch, etc.).

**Διαφορετικά:** Application handling log routing === hard to scale, loss of logs, poor separation of concerns

🔗 [**Διαβάστε Περισσότερα: Log Routing**](/sections/production/logrouting.md)

<br/><br/>

## ![✔] 5.19. Install your packages with `npm ci` 

**Συνοπτικά:** You have to be sure that production code uses the exact version of the packages you have tested it with. Run `npm ci` to strictly do a clean install of your dependencies matching package.json and package-lock.json. Using this command is recommended in automated environments such as continuous integration pipelines.

**Διαφορετικά:** QA will thoroughly test the code and approve a version that will behave differently in production. Even worse, different servers in the same production cluster might run different code.

🔗 [**Διαβάστε Περισσότερα: Use npm ci**](/sections/production/installpackageswithnpmci.md)

<br/><br/><br/>

<p align="right"><a href="#table-of-contents">⬆ Return to top</a></p>

# `6. Security Best Practices`

<div align="center">
<img src="https://img.shields.io/badge/OWASP%20Threats-Top%2010-green.svg" alt="54 items"/>
</div>

## ![✔] 6.1. Embrace linter security rules

<a href="https://www.owasp.org/index.php/Top_10-2017_A1-Injection" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A1:Injection%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A7-Cross-Site_Scripting_(XSS)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20XSS%20-green.svg" alt=""/></a>

**Συνοπτικά:** Make use of security-related linter plugins such as [eslint-plugin-security](https://github.com/nodesecurity/eslint-plugin-security) to catch security vulnerabilities and issues as early as possible, preferably while they're being coded. This can help catching security weaknesses like using eval, invoking a child process or importing a module with a string literal (e.g. user input). Click 'Διαβάστε Περισσότερα' below to see code examples that will get caught by a security linter

**Διαφορετικά:** What could have been a straightforward security weakness during development becomes a major issue in production. Also, the project may not follow consistent code security practices, leading to vulnerabilities being introduced, or sensitive secrets committed into remote repositories

🔗 [**Διαβάστε Περισσότερα: Lint rules**](/sections/security/lintrules.md)

<br/><br/>

## ![✔] 6.2. Limit concurrent requests using a middleware

<a href="https://www.owasp.org/index.php/Denial_of_Service" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20DDOS%20-green.svg" alt=""/></a>

**Συνοπτικά:** DOS attacks are very popular and relatively easy to conduct. Implement rate limiting using an external service such as cloud load balancers, cloud firewalls, nginx, [rate-limiter-flexible](https://www.npmjs.com/package/rate-limiter-flexible) package, or (for smaller and less critical apps) a rate-limiting middleware (e.g. [express-rate-limit](https://www.npmjs.com/package/express-rate-limit))

**Διαφορετικά:** An application could be subject to an attack resulting in a denial of service where real users receive a degraded or unavailable service.

🔗 [**Διαβάστε Περισσότερα: Implement rate limiting**](/sections/security/limitrequests.md)

<br/><br/>

## ![✔] 6.3 Extract secrets from config files or use packages to encrypt them

<a href="https://www.owasp.org/index.php/Top_10-2017_A6-Security_Misconfiguration" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A6:Security%20Misconfiguration%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A3-Sensitive_Data_Exposure" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A3:Sensitive%20Data%20Exposure%20-green.svg" alt=""/></a>

**Συνοπτικά:** Never store plain-text secrets in configuration files or source code. Instead, make use of secret-management systems like Vault products, Kubernetes/Docker Secrets, or using environment variables. As a last resort, secrets stored in source control must be encrypted and managed (rolling keys, expiring, auditing, etc). Make use of pre-commit/push hooks to prevent committing secrets accidentally

**Διαφορετικά:** Source control, even for private repositories, can mistakenly be made public, at which point all secrets are exposed. Access to source control for an external party will inadvertently provide access to related systems (databases, apis, services, etc).

🔗 [**Διαβάστε Περισσότερα: Secret management**](/sections/security/secretmanagement.md)

<br/><br/>

## ![✔] 6.4. Prevent query injection vulnerabilities with ORM/ODM libraries

<a href="https://www.owasp.org/index.php/Top_10-2017_A1-Injection" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A1:Injection%20-green.svg" alt=""/></a>

**Συνοπτικά:** To prevent SQL/NoSQL injection and other malicious attacks, always make use of an ORM/ODM or a database library that escapes data or supports named or indexed parameterized queries, and takes care of validating user input for expected types. Never just use JavaScript template strings or string concatenation to inject values into queries as this opens your application to a wide spectrum of vulnerabilities. All the reputable Node.js data access libraries (e.g. [Sequelize](https://github.com/sequelize/sequelize), [Knex](https://github.com/tgriesser/knex), [mongoose](https://github.com/Automattic/mongoose)) have built-in protection against injection attacks.

**Διαφορετικά:** Unvalidated or unsanitized user input could lead to operator injection when working with MongoDB for NoSQL, and not using a proper sanitization system or ORM will easily allow SQL injection attacks, creating a giant vulnerability.

🔗 [**Διαβάστε Περισσότερα: Query injection prevention using ORM/ODM libraries**](/sections/security/ormodmusage.md)

<br/><br/>

## ![✔] 6.5. Collection of generic security best practices

**Συνοπτικά:** This is a collection of security advice that is not related directly to Node.js - the Node implementation is not much different than any other language. Click Διαβάστε Περισσότερα to skim through.

🔗 [**Διαβάστε Περισσότερα: Common security best practices**](/sections/security/commonsecuritybestpractices.md)

<br/><br/>

## ![✔] 6.6. Adjust the HTTP response headers for enhanced security

<a href="https://www.owasp.org/index.php/Top_10-2017_A6-Security_Misconfiguration" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A6:Security%20Misconfiguration%20-green.svg" alt=""/></a>

**Συνοπτικά:** Your application should be using secure headers to prevent attackers from using common attacks like cross-site scripting (XSS), clickjacking and other malicious attacks. These can be configured easily using modules like [helmet](https://www.npmjs.com/package/helmet).

**Διαφορετικά:** Attackers could perform direct attacks on your application's users, leading to huge security vulnerabilities

🔗 [**Διαβάστε Περισσότερα: Using secure headers in your application**](/sections/security/secureheaders.md)

<br/><br/>

## ![✔] 6.7. Constantly and automatically inspect for vulnerable dependencies

<a href="https://www.owasp.org/index.php/Top_10-2017_A9-Using_Components_with_Known_Vulnerabilities" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A9:Known%20Vulnerabilities%20-green.svg" alt=""/></a>

**Συνοπτικά:** With the npm ecosystem it is common to have many dependencies for a project. Dependencies should always be kept in check as new vulnerabilities are found. Use tools like [npm audit](https://docs.npmjs.com/cli/audit) or [snyk](https://snyk.io/) to track, monitor and patch vulnerable dependencies. Integrate these tools with your CI setup so you catch a vulnerable dependency before it makes it to production.

**Διαφορετικά:** An attacker could detect your web framework and attack all its known vulnerabilities.

🔗 [**Διαβάστε Περισσότερα: Dependency security**](/sections/security/dependencysecurity.md)

<br/><br/>

## ![✔] 6.8. Avoid using the Node.js crypto library for handling passwords, use Bcrypt

<a href="https://www.owasp.org/index.php/Top_10-2017_A2-Broken_Authentication" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A9:Broken%20Authentication%20-green.svg" alt=""/></a>

**Συνοπτικά:** Passwords or secrets (API keys) should be stored using a secure hash + salt function like `bcrypt`, that should be a preferred choice over its JavaScript implementation due to performance and security reasons.

**Διαφορετικά:** Passwords or secrets that are persisted without using a secure function are vulnerable to brute forcing and dictionary attacks that will lead to their disclosure eventually.

🔗 [**Διαβάστε Περισσότερα: Use Bcrypt**](/sections/security/bcryptpasswords.md)

<br/><br/>

## ![✔] 6.9. Escape HTML, JS and CSS output

<a href="https://www.owasp.org/index.php/Top_10-2017_A7-Cross-Site_Scripting_(XSS)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A7:XSS%20-green.svg" alt=""/></a>

**Συνοπτικά:** Untrusted data that is sent down to the browser might get executed instead of just being displayed, this is commonly referred as a cross-site-scripting (XSS) attack. Mitigate this by using dedicated libraries that explicitly mark the data as pure content that should never get executed (i.e. encoding, escaping)

**Διαφορετικά:** An attacker might store malicious JavaScript code in your DB which will then be sent as-is to the poor clients

🔗 [**Διαβάστε Περισσότερα: Escape output**](/sections/security/escape-output.md)

<br/><br/>

## ![✔] 6.10. Validate incoming JSON schemas

<a href="https://www.owasp.org/index.php/Top_10-2017_A7-Cross-Site_Scripting_(XSS)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A7: XSS%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A8-Insecure_Deserialization" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A8:Insecured%20Deserialization%20-green.svg" alt=""/></a>

**Συνοπτικά:** Validate the incoming requests' body payload and ensure it meets expectations, fail fast if it doesn't. To avoid tedious validation coding within each route you may use lightweight JSON-based validation schemas such as [jsonschema](https://www.npmjs.com/package/jsonschema) or [joi](https://www.npmjs.com/package/joi)

**Διαφορετικά:** Your generosity and permissive approach greatly increases the attack surface and encourages the attacker to try out many inputs until they find some combination to crash the application

🔗 [**Διαβάστε Περισσότερα: Validate incoming JSON schemas**](/sections/security/validation.md)

<br/><br/>

## ![✔] 6.11. Support blacklisting JWTs

<a href="https://www.owasp.org/index.php/Top_10-2017_A2-Broken_Authentication" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A9:Broken%20Authentication%20-green.svg" alt=""/></a>

**Συνοπτικά:** When using JSON Web Tokens (for example, with [Passport.js](https://github.com/jaredhanson/passport)), by default there's no mechanism to revoke access from issued tokens. Once you discover some malicious user activity, there's no way to stop them from accessing the system as long as they hold a valid token. Mitigate this by implementing a blacklist of untrusted tokens that are validated on each request.

**Διαφορετικά:** Expired, or misplaced tokens could be used maliciously by a third party to access an application and impersonate the owner of the token.

🔗 [**Διαβάστε Περισσότερα: Blacklist JSON Web Tokens**](/sections/security/expirejwt.md)

<br/><br/>

## ![✔] 6.12. Prevent brute-force attacks against authorization

<a href="https://www.owasp.org/index.php/Top_10-2017_A2-Broken_Authentication" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A9:Broken%20Authentication%20-green.svg" alt=""/></a>

**Συνοπτικά:** A simple and powerful technique is to limit authorization attempts using two metrics:

1. The first is number of consecutive failed attempts by the same user unique ID/name and IP address.
2. The second is number of failed attempts from an IP address over some long period of time. For example, block an IP address if it makes 100 failed attempts in one day.

**Διαφορετικά:** An attacker can issue unlimited automated password attempts to gain access to privileged accounts on an application

🔗 [**Διαβάστε Περισσότερα: Login rate limiting**](/sections/security/login-rate-limit.md)

<br/><br/>

## ![✔] 6.13. Run Node.js as non-root user

<a href="https://www.owasp.org/index.php/Top_10-2017_A5-Broken_Access_Control" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A5:Broken%20Access%20Access%20Control-green.svg" alt=""/></a>

**Συνοπτικά:** There is a common scenario where Node.js runs as a root user with unlimited permissions. For example, this is the default behaviour in Docker containers. It's recommended to create a non-root user and either bake it into the Docker image (examples given below) or run the process on this user's behalf by invoking the container with the flag "-u username"

**Διαφορετικά:** An attacker who manages to run a script on the server gets unlimited power over the local machine (e.g. change iptable and re-route traffic to his server)

🔗 [**Διαβάστε Περισσότερα: Run Node.js as non-root user**](/sections/security/non-root-user.md)

<br/><br/>

## ![✔] 6.14. Limit payload size using a reverse-proxy or a middleware

<a href="https://www.owasp.org/index.php/Top_10-2017_A8-Insecure_Deserialization" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A8:Insecured%20Deserialization%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A1-Injection" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20DDOS%20-green.svg" alt=""/></a>

**Συνοπτικά:** The bigger the body payload is, the harder your single thread works in processing it. This is an opportunity for attackers to bring servers to their knees without tremendous amount of requests (DOS/DDOS attacks). Mitigate this limiting the body size of incoming requests on the edge (e.g. firewall, ELB) or by configuring [express body parser](https://github.com/expressjs/body-parser) to accept only small-size payloads

**Διαφορετικά:** Your application will have to deal with large requests, unable to process the other important work it has to accomplish, leading to performance implications and vulnerability towards DOS attacks

🔗 [**Διαβάστε Περισσότερα: Limit payload size**](/sections/security/requestpayloadsizelimit.md)

<br/><br/>

## ![✔] 6.15. Avoid JavaScript eval statements

<a href="https://www.owasp.org/index.php/Top_10-2017_A7-Cross-Site_Scripting_(XSS)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A7:XSS%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A1-Injection" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A1:Injection%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A4-XML_External_Entities_(XXE)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A4:External%20Entities%20-green.svg" alt=""/></a>

**Συνοπτικά:** `eval` is evil as it allows executing custom JavaScript code during run time. This is not just a performance concern but also an important security concern due to malicious JavaScript code that may be sourced from user input. Another language feature that should be avoided is `new Function` constructor. `setTimeout` and `setInterval` should never be passed dynamic JavaScript code either.

**Διαφορετικά:** Malicious JavaScript code finds a way into text passed into `eval` or other real-time evaluating JavaScript language functions, and will gain complete access to JavaScript permissions on the page. This vulnerability is often manifested as an XSS attack.

🔗 [**Διαβάστε Περισσότερα: Avoid JavaScript eval statements**](/sections/security/avoideval.md)

<br/><br/>

## ![✔] 6.16. Prevent evil RegEx from overloading your single thread execution

<a href="https://www.owasp.org/index.php/Denial_of_Service" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20DDOS%20-green.svg" alt=""/></a>

**Συνοπτικά:** Regular Expressions, while being handy, pose a real threat to JavaScript applications at large, and the Node.js platform in particular. A user input for text to match might require an outstanding amount of CPU cycles to process. RegEx processing might be inefficient to an extent that a single request that validates 10 words can block the entire event loop for 6 seconds and set the CPU on 🔥. For that reason, prefer third-party validation packages like [validator.js](https://github.com/chriso/validator.js) instead of writing your own Regex patterns, or make use of [safe-regex](https://github.com/substack/safe-regex) to detect vulnerable regex patterns

**Διαφορετικά:** Poorly written regexes could be susceptible to Regular Expression DoS attacks that will block the event loop completely. For example, the popular `moment` package was found vulnerable with malicious RegEx usage in November of 2017

🔗 [**Διαβάστε Περισσότερα: Prevent malicious RegEx**](/sections/security/regex.md)

<br/><br/>

## ![✔] 6.17. Avoid module loading using a variable

<a href="https://www.owasp.org/index.php/Top_10-2017_A7-Cross-Site_Scripting_(XSS)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A7:XSS%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A1-Injection" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A1:Injection%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A4-XML_External_Entities_(XXE)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A4:External%20Entities%20-green.svg" alt=""/></a>

**Συνοπτικά:** Avoid requiring/importing another file with a path that was given as parameter due to the concern that it could have originated from user input. This rule can be extended for accessing files in general (i.e. `fs.readFile()`) or other sensitive resource access with dynamic variables originating from user input. [Eslint-plugin-security](https://www.npmjs.com/package/eslint-plugin-security) linter can catch such patterns and warn early enough

**Διαφορετικά:** Malicious user input could find its way to a parameter that is used to require tampered files, for example, a previously uploaded file on the file system, or access already existing system files.

🔗 [**Διαβάστε Περισσότερα: Safe module loading**](/sections/security/safemoduleloading.md)

<br/><br/>

## ![✔] 6.18. Run unsafe code in a sandbox

<a href="https://www.owasp.org/index.php/Top_10-2017_A7-Cross-Site_Scripting_(XSS)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A7:XSS%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A1-Injection" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A1:Injection%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A4-XML_External_Entities_(XXE)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A4:External%20Entities%20-green.svg" alt=""/></a>

**Συνοπτικά:** When tasked to run external code that is given at run-time (e.g. plugin), use any sort of 'sandbox' execution environment that isolates and guards the main code against the plugin. This can be achieved using a dedicated process (e.g. `cluster.fork()`), serverless environment or dedicated npm packages that act as a sandbox

**Διαφορετικά:** A plugin can attack through an endless variety of options like infinite loops, memory overloading, and access to sensitive process environment variables

🔗 [**Διαβάστε Περισσότερα: Run unsafe code in a sandbox**](/sections/security/sandbox.md)

<br/><br/>

## ![✔] 6.19. Take extra care when working with child processes

<a href="https://www.owasp.org/index.php/Top_10-2017_A7-Cross-Site_Scripting_(XSS)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A7:XSS%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A1-Injection" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A1:Injection%20-green.svg" alt=""/></a> <a href="https://www.owasp.org/index.php/Top_10-2017_A4-XML_External_Entities_(XXE)" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A4:External%20Entities%20-green.svg" alt=""/></a>

**Συνοπτικά:** Avoid using child processes when possible and validate and sanitize input to mitigate shell injection attacks if you still have to. Prefer using `child_process.execFile` which by definition will only execute a single command with a set of attributes and will not allow shell parameter expansion.

**Διαφορετικά:** Naive use of child processes could result in remote command execution or shell injection attacks due to malicious user input passed to an unsanitized system command.

🔗 [**Διαβάστε Περισσότερα: Be cautious when working with child processes**](/sections/security/childprocesses.md)

<br/><br/>

## ![✔] 6.20. Hide error details from clients

<a href="https://www.owasp.org/index.php/Top_10-2017_A6-Security_Misconfiguration" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A6:Security%20Misconfiguration%20-green.svg" alt=""/></a>

**Συνοπτικά:** An integrated express error handler hides the error details by default. However, great are the chances that you implement your own error handling logic with custom Error objects (considered by many as a best practice). If you do so, ensure not to return the entire Error object to the client, which might contain some sensitive application details

**Διαφορετικά:** Sensitive application details such as server file paths, third party modules in use, and other internal workflows of the application which could be exploited by an attacker, could be leaked from information found in a stack trace

🔗 [**Διαβάστε Περισσότερα: Hide error details from client**](/sections/security/hideerrors.md)

<br/><br/>

## ![✔] 6.21. Configure 2FA for npm or Yarn

<a href="https://www.owasp.org/index.php/Top_10-2017_A6-Security_Misconfiguration" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A6:Security%20Misconfiguration%20-green.svg" alt=""/></a>

**Συνοπτικά:** Any step in the development chain should be protected with MFA (multi-factor authentication), npm/Yarn are a sweet opportunity for attackers who can get their hands on some developer's password. Using developer credentials, attackers can inject malicious code into libraries that are widely installed across projects and services. Maybe even across the web if published in public. Enabling 2-factor-authentication in npm leaves almost zero chances for attackers to alter your package code.

**Διαφορετικά:** [Have you heard about the eslint developer whose password was hijacked?](https://medium.com/@oprearocks/eslint-backdoor-what-it-is-and-how-to-fix-the-issue-221f58f1a8c8)

<br/><br/>

## ![✔] 6.22. Modify session middleware settings

<a href="https://www.owasp.org/index.php/Top_10-2017_A6-Security_Misconfiguration" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A6:Security%20Misconfiguration%20-green.svg" alt=""/></a>

**Συνοπτικά:** Each web framework and technology has its known weaknesses - telling an attacker which web framework we use is a great help for them. Using the default settings for session middlewares can expose your app to module- and framework-specific hijacking attacks in a similar way to the `X-Powered-By` header. Try hiding anything that identifies and reveals your tech stack (E.g. Node.js, express)

**Διαφορετικά:** Cookies could be sent over insecure connections, and an attacker might use session identification to identify the underlying framework of the web application, as well as module-specific vulnerabilities

🔗 [**Διαβάστε Περισσότερα: Cookie and session security**](/sections/security/sessions.md)

<br/><br/>

## ![✔] 6.23. Avoid DOS attacks by explicitly setting when a process should crash

<a href="https://www.owasp.org/index.php/Denial_of_Service" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20DDOS%20-green.svg" alt=""/></a>

**Συνοπτικά:** The Node process will crash when errors are not handled. Many best practices even recommend to exit even though an error was caught and got handled. Express, for example, will crash on any asynchronous error - unless you wrap routes with a catch clause. This opens a very sweet attack spot for attackers who recognize what input makes the process crash and repeatedly send the same request. There's no instant remedy for this but a few techniques can mitigate the pain: Alert with critical severity anytime a process crashes due to an unhandled error, validate the input and avoid crashing the process due to invalid user input, wrap all routes with a catch and consider not to crash when an error originated within a request (as opposed to what happens globally)

**Διαφορετικά:** This is just an educated guess: given many Node.js applications, if we try passing an empty JSON body to all POST requests - a handful of applications will crash. At that point, we can just repeat sending the same request to take down the applications with ease

<br/><br/>

## ![✔] 6.24. Prevent unsafe redirects

<a href="https://www.owasp.org/index.php/Top_10-2017_A1-Injection" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A1:Injection%20-green.svg" alt=""/></a>

**Συνοπτικά:** Redirects that do not validate user input can enable attackers to launch phishing scams, steal user credentials, and perform other malicious actions.

**Διαφορετικά:** If an attacker discovers that you are not validating external, user-supplied input, they may exploit this vulnerability by posting specially-crafted links on forums, social media, and other public places to get users to click it.

🔗 [**Διαβάστε Περισσότερα: Prevent unsafe redirects**](/sections/security/saferedirects.md)

<br/><br/>

## ![✔] 6.25. Avoid publishing secrets to the npm registry

<a href="https://www.owasp.org/index.php/Top_10-2017_A6-Security_Misconfiguration" target="_blank"><img src="https://img.shields.io/badge/%E2%9C%94%20OWASP%20Threats%20-%20A6:Security%20Misconfiguration%20-green.svg" alt=""/></a>

**Συνοπτικά:** Precautions should be taken to avoid the risk of accidentally publishing secrets to public npm registries. An `.npmignore` file can be used to blacklist specific files or folders, or the `files` array in `package.json` can act as a whitelist.

**Διαφορετικά:** Your project's API keys, passwords or other secrets are open to be abused by anyone who comes across them, which may result in financial loss, impersonation, and other risks.

🔗 [**Διαβάστε Περισσότερα: Avoid publishing secrets**](/sections/security/avoid_publishing_secrets.md)
<br/><br/><br/>

<p align="right"><a href="#table-of-contents">⬆ Return to top</a></p>

# `7. Draft: Performance Best Practices`

## Our contributors are working on this section. [Would you like to join?](https://github.com/goldbergyoni/nodebestpractices/issues/256)

<br/><br/>

## ![✔] 7.1. Don't block the event loop

**Συνοπτικά:** Avoid CPU intensive tasks as they will block the mostly single-threaded Event Loop and offload those to a dedicated thread, process or even a different technology based on the context.

**Διαφορετικά:** As the Event Loop is blocked, Node.js will be unable to handle other request thus causing delays for concurrent users. **3000 users are waiting for a response, the content is ready to be served, but one single request blocks the server from dispatching the results back**

🔗 [**Διαβάστε Περισσότερα: Do not block the event loop**](/sections/performance/block-loop.md)

<br /><br /><br />

## ![✔] 7.2. Prefer native JS methods over user-land utils like Lodash

**Συνοπτικά:** It's often more penalising to use utility libraries like `lodash` and `underscore` over native methods as it leads to unneeded dependencies and slower performance.
Bear in mind that with the introduction of the new V8 engine alongside the new ES standards, native methods were improved in such a way that it's now about 50% more performant than utility libraries.

**Διαφορετικά:** You'll have to maintain less performant projects where you could have simply used what was **already** available or dealt with a few more lines in exchange of a few more files.

🔗 [**Διαβάστε Περισσότερα: Native over user land utils**](/sections/performance/nativeoverutil.md)

<br/><br/><br/>

<p align="right"><a href="#table-of-contents">⬆ Return to top</a></p>

# `8. Docker Best Practices`

🏅 Many thanks to [Bret Fisher](https://github.com/BretFisher) from whom we learned many of the following practices

<br/><br/>

## ![✔] 8.1 Use multi-stage builds for leaner and more secure Docker images

**Συνοπτικά:** Use multi-stage build to copy only necessary production artifacts. A lot of build-time dependencies and files are not needed for running your application. With multi-stage builds these resources can be used during build while the runtime environment contains only what's necessary. Multi-stage builds are an easy way to get rid of overweight and security threats.

**Διαφορετικά:** Larger images will take longer to build and ship, build-only tools might contain vulnerabilities and secrets only meant for the build phase might be leaked.

### Example Dockerfile for multi-stage builds

```dockerfile
FROM node:14.4.0 AS build

COPY . .
RUN npm ci && npm run build

FROM node:slim-14.4.0

USER node
EXPOSE 8080

COPY --from=build /home/node/app/dist /home/node/app/package.json /home/node/app/package-lock.json ./
RUN npm ci --production

CMD [ "node", "dist/app.js" ]
```

🔗 [**Διαβάστε Περισσότερα: Use multi-stage builds**](/sections/docker/multi_stage_builds.md)

<br /><br /><br />

## ![✔] 8.2. Bootstrap using 'node' command, avoid npm start

**Συνοπτικά:** use `CMD ['node','server.js']` to start your app, avoid using npm scripts which don't pass OS signals to the code. This prevents problems with child-process, signal handling, graceful shutdown and having zombie processes.

**Διαφορετικά:** When no signals are passed, your code will never be notified about shutdowns. Without this, it will lose its chance to close properly possibly losing current requests and/or data.

[**Διαβάστε Περισσότερα: Bootstrap container using node command, avoid npm start**](/sections/docker/bootstrap-using-node.md)

<br /><br /><br />

## ![✔] 8.3. Let the Docker runtime handle replication and uptime

**Συνοπτικά:** When using a Docker run time orchestrator (e.g., Kubernetes), invoke the Node.js process directly without intermediate process managers or custom code that replicate the process (e.g. PM2, Cluster module). The runtime platform has the highest amount of data and visibility for making placement decision - It knows best how many processes are needed, how to spread them and what to do in case of crashes

**Διαφορετικά:** Container keeps crashing due to lack of resources will get restarted indefinitely by the process manager. Should Kubernetes be aware of that, it could relocate it to a different roomy instance

🔗 [**Διαβάστε Περισσότερα: Let the Docker orchestrator restart and replicate processes**](/sections/docker/restart-and-replicate-processes.md)

<br/><br /><br />

## ![✔] 8.4. Use .dockerignore to prevent leaking secrets

**Συνοπτικά**: Include a `.dockerignore` file that filters out common secret files and development artifacts. By doing so, you might prevent secrets from leaking into the image. As a bonus the build time will significantly decrease. Also, ensure not to copy all files recursively rather explicitly choose what should be copied to Docker

**Διαφορετικά**: Common personal secret files like `.env`, `.aws` and `.npmrc` will be shared with anybody with access to the image (e.g. Docker repository)

🔗 [**Διαβάστε Περισσότερα: Use .dockerignore**](/sections/docker/docker-ignore.md)

<br /><br /><br />

## ![✔] 8.5. Clean-up dependencies before production

**Συνοπτικά:** Although Dev-Dependencies are sometimes needed during the build and test life-cycle, eventually the image that is shipped to production should be minimal and clean from development dependencies. Doing so guarantees that only necessary code is shipped and the amount of potential attacks (i.e. attack surface) is minimized. When using multi-stage build (see dedicated bullet) this can be achieved by installing all dependencies first and finally running `npm ci --production`

**Διαφορετικά:** Many of the infamous npm security breaches were found within development packages (e.g. [eslint-scope](https://eslint.org/blog/2018/07/postmortem-for-malicious-package-publishes))

🔗 Διαβάστε Περισσότερα: [Remove development dependencies](/sections/docker/install-for-production.md)

<br /><br /><br />

## ![✔] 8.6. Shutdown smartly and gracefully

**Συνοπτικά:** Handle the process SIGTERM event and clean-up all existing connection and resources. This should be done while responding to ongoing requests. In Dockerized runtimes shutting down containers is not a rare event, rather a frequent occurrence that happen as part of routine work. Achieving this demands some thoughtful code to orchestrate several moving parts: The load balancer, keep-alive connections, the HTTP server and other resources

**Διαφορετικά:** Dying immediately means not responding to thousands of disappointed users

🔗 [**Διαβάστε Περισσότερα: Graceful shutdown**](/sections/docker/graceful-shutdown.md)

<br /><br /><br />

## ![✔] 8.7. Set memory limits using both Docker and v8

**Συνοπτικά:** Always configure a memory limit using both Docker and the JavaScript runtime flags. The Docker limit is needed to make thoughtful container placement decision, the --v8's flag max-old-space is needed to kick off the GC on time and prevent under utilization of memory. Practically, set the v8's old space memory to be a just bit less than the container limit

**Διαφορετικά:** The docker definition is needed to perform thoughtful scaling decision and prevent starving other citizens. Without also defining the v8's limits, it will under utilize the container resources - Without explicit instructions it crashes when utilizing ~50-60% of its host resources

🔗 [**Διαβάστε Περισσότερα: Set memory limits using Docker only**](/sections/docker/memory-limit.md)

<br /><br /><br />

## ![✔] 8.8. Plan for efficient caching

**Συνοπτικά:** Rebuilding a whole docker image from cache can be nearly instantaneous if done correctly. The less updated instructions should be at the top of your Dockerfile and the ones constantly changing (like app code) should be at the bottom.

**Διαφορετικά:** Docker build will be very long and consume lot of resources even when making tiny changes

🔗 [**Διαβάστε Περισσότερα: Leverage caching to reduce build times**](/sections/docker/use-cache-for-shorter-build-time.md)

<br /><br /><br />

## ![✔] 8.9. Use explicit image reference, avoid `latest` tag

**Συνοπτικά:** Specify an explicit image digest or versioned label, never refer to `latest`. Developers are often led to believe that specifying the `latest` tag will provide them with the most recent image in the repository however this is not the case. Using a digest guarantees that every instance of the service is running exactly the same code.

In addition, referring to an image tag means that the base image is subject to change, as image tags cannot be relied upon for a deterministic install. Instead, if a deterministic install is expected, a SHA256 digest can be used to reference an exact image.

**Διαφορετικά:** A new version of a base image could be deployed into production with breaking changes, causing unintended application behaviour.

🔗 [**Διαβάστε Περισσότερα: Understand image tags and use the "latest" tag with caution**](/sections/docker/image-tags.md)

<br /><br /><br />

## ![✔] 8.10. Prefer smaller Docker base images

**Συνοπτικά:** Large images lead to higher exposure to vulnerabilities and increased resource consumption. Using leaner Docker images, such as Slim and Alpine Linux variants, mitigates this issue.

**Διαφορετικά:** Building, pushing, and pulling images will take longer, unknown attack vectors can be used by malicious actors and more resources are consumed.

🔗 [**Διαβάστε Περισσότερα: Prefer smaller images**](/sections/docker/smaller_base_images.md)

<br /><br /><br />

## ![✔] 8.11. Clean-out build-time secrets, avoid secrets in args

**Συνοπτικά:** Avoid secrets leaking from the Docker build environment. A Docker image is typically shared in multiple environment like CI and a registry that are not as sanitized as production. A typical example is an npm token which is usually passed to a dockerfile as argument. This token stays within the image long after it is needed and allows the attacker indefinite access to a private npm registry. This can be avoided by coping a secret file like `.npmrc` and then removing it using multi-stage build (beware, build history should be deleted as well) or by using Docker build-kit secret feature which leaves zero traces

**Διαφορετικά:** Everyone with access to the CI and docker registry will also get access to some precious organization secrets as a bonus

🔗 [**Διαβάστε Περισσότερα: Clean-out build-time secrets**](/sections/docker/avoid-build-time-secrets.md)

<br /><br /><br />

## ![✔] 8.12. Scan images for multi layers of vulnerabilities

**Συνοπτικά:** Besides checking code dependencies vulnerabilities also scan the final image that is shipped to production. Docker image scanners check the code dependencies but also the OS binaries. This E2E security scan covers more ground and verifies that no bad guy injected bad things during the build. Consequently, it is recommended running this as the last step before deployment. There are a handful of free and commercial scanners that also provide CI/CD plugins

**Διαφορετικά:** Your code might be entirely free from vulnerabilities. However it might still get hacked due to vulnerable version of OS-level binaries (e.g. OpenSSL, TarBall) that are commonly being used by applications

🔗 [**Διαβάστε Περισσότερα: Generic Docker practices**](/sections/docker/scan-images.md)

<br /><br /><br />

## ![✔] 8.13 Clean NODE_MODULE cache

**Συνοπτικά:** After installing dependencies in a container remove the local cache. It doesn't make any sense to duplicate the dependencies for faster future installs since there won't be any further installs - A Docker image is immutable. Using a single line of code tens of MB (typically 10-50% of the image size) are shaved off

**Διαφορετικά:** The image that will get shipped to production will weigh 30% more due to files that will never get used

🔗 [**Διαβάστε Περισσότερα: Clean NODE_MODULE cache**](/sections/docker/clean-cache.md)

<br /><br /><br />

## ![✔] 8.14. Generic Docker practices

**Συνοπτικά:** This is a collection of Docker advice that is not related directly to Node.js - the Node implementation is not much different than any other language. Click Διαβάστε Περισσότερα to skim through.

🔗 [**Διαβάστε Περισσότερα: Generic Docker practices**](/sections/docker/generic-tips.md)

<br/><br /><br />


## ![✔] 8.15. Lint your Dockerfile

**Συνοπτικά:** Linting your Dockerfile is an important step to identify issues in your Dockerfile which differ from best practices. By checking for potential flaws using a specialised Docker linter, performance and security improvements can be easily identified, saving countless hours of wasted time or security issues in production code.

**Διαφορετικά:** Mistakenely the Dockerfile creator left Root as the production user, and also used an image from unknown source repository. This could be avoided with with just a simple linter.

🔗 [**Διαβάστε Περισσότερα: Lint your Dockerfile**](/sections/docker/lint-dockerfile.md)

<br/><br /><br />

<p align="right"><a href="#table-of-contents">⬆ Return to top</a></p>

# Milestones

To maintain this guide and keep it up to date, we are constantly updating and improving the guidelines and best practices with the help of the community. You can follow our [milestones](https://github.com/goldbergyoni/nodebestpractices/milestones) and join the working groups if you want to contribute to this project

<br/>

## Translations

All translations are contributed by the community. We will be happy to get any help with either completed, ongoing or new translations!

### Completed translations

- ![BR](/assets/flags/BR.png) [Brazilian Portuguese](./README.brazilian-portuguese.md) - Courtesy of [Marcelo Melo](https://github.com/marcelosdm)
- ![CN](/assets/flags/CN.png) [Chinese](./README.chinese.md) - Courtesy of [Matt Jin](https://github.com/mattjin)
- ![RU](/assets/flags/RU.png) [Russian](./README.russian.md) - Courtesy of [Alex Ivanov](https://github.com/contributorpw)
- ![PL](/assets/flags/PL.png) [Polish](./README.polish.md) - Courtesy of [Michal Biesiada](https://github.com/mbiesiad)

### Translations in progress

- ![FR](/assets/flags/FR.png) [French](https://github.com/gaspaonrocks/nodebestpractices/blob/french-translation/README.french.md) ([Discussion](https://github.com/goldbergyoni/nodebestpractices/issues/129))
- ![HE](/assets/flags/HE.png) Hebrew ([Discussion](https://github.com/goldbergyoni/nodebestpractices/issues/156))
- ![KR](/assets/flags/KR.png) [Korean](README.korean.md) - Courtesy of [Sangbeom Han](https://github.com/uronly14me) ([Discussion](https://github.com/goldbergyoni/nodebestpractices/issues/94))
- ![ES](/assets/flags/ES.png) [Spanish](https://github.com/goldbergyoni/nodebestpractices/blob/spanish-translation/README.spanish.md) ([Discussion](https://github.com/goldbergyoni/nodebestpractices/issues/95))
- ![TR](/assets/flags/TR.png) Turkish ([Discussion](https://github.com/goldbergyoni/nodebestpractices/issues/139))

<br/><br/>

## Steering Committee

Meet the steering committee members - the people who work together to provide guidance and future direction to the project. In addition, each member of the committee leads a project tracked under our [Github projects](https://github.com/goldbergyoni/nodebestpractices/projects).

<img align="left" width="100" height="100" src="assets/images/members/yoni.png">

[Yoni Goldberg](https://github.com/goldbergyoni)
<a href="https://twitter.com/goldbergyoni"><img src="assets/images/twitter-s.png" width="16" height="16"></img></a>
<a href="https://goldbergyoni.com"><img src="assets/images/www.png" width="16" height="16"></img></a>

Independent Node.js consultant who works with customers in the USA, Europe, and Israel on building large-scale Node.js applications. Many of the best practices above were first published at [goldbergyoni.com](https://goldbergyoni.com). Reach Yoni at [@goldbergyoni](https://github.com/goldbergyoni) or [me@goldbergyoni.com](mailto:me@goldbergyoni.com)

<br/>

<img align="left" width="100" height="100" src="assets/images/members/bruno.png">

[Bruno Scheufler](https://github.com/BrunoScheufler)
<a href="https://brunoscheufler.com/"><img src="assets/images/www.png" width="16" height="16"></img></a>

💻 full-stack web engineer, Node.js & GraphQL enthusiast

<br/>

<img align="left" width="100" height="100" src="assets/images/members/kyle.png">

[Kyle Martin](https://github.com/js-kyle)
<a href="https://twitter.com/kylemartin_93"><img src="assets/images/twitter-s.png" width="16" height="16"></img></a>
<a href="https://www.linkedin.com/in/kylemartinnz"><img src="assets/images/linkedin.png" width="16" height="16"></img></a>

Full Stack Developer & Site Reliability Engineer based in New Zealand, interested in web application security, and architecting and building Node.js applications to perform at global scale.

<br/>

<img align="left" width="100" height="100" src="assets/images/members/kevyn.png">

[Kevyn Bruyere](https://github.com/kevynb)
<a href="https://www.linkedin.com/in/kevynbruyere/"><img src="assets/images/linkedin.png" width="16" height="16"></img></a>

Independent full-stack developer with a taste for Ops and automation.

<br/>

### Steering Committee Emeriti

<img align="left" width="100" height="100" src="assets/images/members/sagir.png">

[Sagir Khan](https://github.com/sagirk)
<a href="https://twitter.com/sagir_k"><img src="assets/images/twitter-s.png" width="16" height="16"></img></a>
<a href="https://linkedin.com/in/sagirk"><img src="assets/images/linkedin.png" width="16" height="16"></img></a>
<a href="https://sagirk.com"><img src="assets/images/www.png" width="16" height="16"></img></a>

Deep specialist in JavaScript and its ecosystem — React, Node.js, TypeScript, GraphQL, MongoDB, pretty much anything that involves JS/JSON in any layer of the system — building products using the web platform for the world’s most recognized brands. Individual Member of the Node.js Foundation.

<br/>

## Collaborators

Thank you to all our collaborators! 🙏

Our collaborators are members who are contributing to the repository on a regular basis, through suggesting new best practices, triaging issues, reviewing pull requests and more. If you are interested in helping us guide thousands of people to craft better Node.js applications, please read our [contributor guidelines](/.operations/CONTRIBUTING.md) 🎉

| <a href="https://github.com/idori" target="_blank"><img src="assets/images/members/ido.png" width="75" height="75"></a> | <a href="https://github.com/TheHollidayInn" target="_blank"><img src="assets/images/members/keith.png" width="75" height="75"></a> |
| :---------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: |
|                                    [Ido Richter (Founder)](https://github.com/idori)                                    |                                        [Keith Holliday](https://github.com/TheHollidayInn)                                         |

### Collaborator Emeriti

| <a href="https://github.com/refack" target="_blank"><img src="assets/images/members/refael.png" width="50" height="50"></a> |
| :-------------------------------------------------------------------------------------------------------------------------: |
|                                        [Refael Ackermann](https://github.com/refack)                                        |

<br/>

## Contributing
If you've ever wanted to contribute to open source, now is your chance! See the [contributing docs](.operations/CONTRIBUTING.md) for more information.

## Contributors ✨

Thanks goes to these wonderful people who have contributed to this repository!

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/kevinrambaud"><img src="https://avatars1.githubusercontent.com/u/7501477?v=4" width="100px;" alt=""/><br /><sub><b>Kevin Rambaud</b></sub></a><br /><a href="#content-kevinrambaud" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/mfine15"><img src="https://avatars1.githubusercontent.com/u/1286554?v=4" width="100px;" alt=""/><br /><sub><b>Michael Fine</b></sub></a><br /><a href="#content-mfine15" title="Content">🖋</a></td>
    <td align="center"><a href="http://squgeim.github.io"><img src="https://avatars0.githubusercontent.com/u/4996818?v=4" width="100px;" alt=""/><br /><sub><b>Shreya Dahal</b></sub></a><br /><a href="#content-squgeim" title="Content">🖋</a></td>
    <td align="center"><a href="http://matheusrocha89.com"><img src="https://avatars1.githubusercontent.com/u/3718366?v=4" width="100px;" alt=""/><br /><sub><b>Matheus Cruz Rocha</b></sub></a><br /><a href="#content-matheusrocha89" title="Content">🖋</a></td>
    <td align="center"><a href="https://bityog.github.io/Portfolio/"><img src="https://avatars2.githubusercontent.com/u/28219178?v=4" width="100px;" alt=""/><br /><sub><b>Yog Mehta</b></sub></a><br /><a href="#content-BitYog" title="Content">🖋</a></td>
    <td align="center"><a href="http://kudapara.co.zw"><img src="https://avatars3.githubusercontent.com/u/13519184?v=4" width="100px;" alt=""/><br /><sub><b>Kudakwashe Paradzayi</b></sub></a><br /><a href="#content-kudapara" title="Content">🖋</a></td>
    <td align="center"><a href="https://www.t1st3.com/"><img src="https://avatars1.githubusercontent.com/u/1469638?v=4" width="100px;" alt=""/><br /><sub><b>t1st3</b></sub></a><br /><a href="#content-t1st3" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/mulijordan1976"><img src="https://avatars0.githubusercontent.com/u/33382022?v=4" width="100px;" alt=""/><br /><sub><b>mulijordan1976</b></sub></a><br /><a href="#content-mulijordan1976" title="Content">🖋</a></td>
    <td align="center"><a href="https://twitter.com/matchai"><img src="https://avatars0.githubusercontent.com/u/4658208?v=4" width="100px;" alt=""/><br /><sub><b>Matan Kushner</b></sub></a><br /><a href="#content-matchai" title="Content">🖋</a></td>
    <td align="center"><a href="https://fabiothiroki.github.io"><img src="https://avatars2.githubusercontent.com/u/670057?v=4" width="100px;" alt=""/><br /><sub><b>Fabio Hiroki</b></sub></a><br /><a href="#content-fabiothiroki" title="Content">🖋</a></td>
    <td align="center"><a href="http://james.sumners.info/"><img src="https://avatars1.githubusercontent.com/u/321201?v=4" width="100px;" alt=""/><br /><sub><b>James Sumners</b></sub></a><br /><a href="#content-jsumners" title="Content">🖋</a></td>
    <td align="center"><a href="https://twitter.com/_DanGamble"><img src="https://avatars2.githubusercontent.com/u/7152041?v=4" width="100px;" alt=""/><br /><sub><b>Dan Gamble</b></sub></a><br /><a href="#content-dan-gamble" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/trainorpj"><img src="https://avatars3.githubusercontent.com/u/13276704?v=4" width="100px;" alt=""/><br /><sub><b>PJ Trainor</b></sub></a><br /><a href="#content-trainorpj" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/reod"><img src="https://avatars0.githubusercontent.com/u/3164299?v=4" width="100px;" alt=""/><br /><sub><b>Remek Ambroziak</b></sub></a><br /><a href="#content-reod" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://ca.non.co.il"><img src="https://avatars0.githubusercontent.com/u/1829789?v=4" width="100px;" alt=""/><br /><sub><b>Yoni Jah</b></sub></a><br /><a href="#content-yonjah" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/hazolsky"><img src="https://avatars1.githubusercontent.com/u/1270790?v=4" width="100px;" alt=""/><br /><sub><b>Misha Khokhlov</b></sub></a><br /><a href="#content-hazolsky" title="Content">🖋</a></td>
    <td align="center"><a href="https://plus.google.com/+ЕвгенийОрехов/"><img src="https://avatars3.githubusercontent.com/u/8045060?v=4" width="100px;" alt=""/><br /><sub><b>Evgeny Orekhov</b></sub></a><br /><a href="#content-EvgenyOrekhov" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/gediminasml"><img src="https://avatars3.githubusercontent.com/u/19854105?v=4" width="100px;" alt=""/><br /><sub><b>-</b></sub></a><br /><a href="#content-gediminasml" title="Content">🖋</a></td>
    <td align="center"><a href="http://hisaac.net"><img src="https://avatars3.githubusercontent.com/u/923876?v=4" width="100px;" alt=""/><br /><sub><b>Isaac Halvorson</b></sub></a><br /><a href="#content-hisaac" title="Content">🖋</a></td>
    <td align="center"><a href="http://www.vedrankaracic.com"><img src="https://avatars3.githubusercontent.com/u/2808092?v=4" width="100px;" alt=""/><br /><sub><b>Vedran Karačić</b></sub></a><br /><a href="#content-vkaracic" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/lallenlowe"><img src="https://avatars3.githubusercontent.com/u/10761165?v=4" width="100px;" alt=""/><br /><sub><b>lallenlowe</b></sub></a><br /><a href="#content-lallenlowe" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/nwwells"><img src="https://avatars2.githubusercontent.com/u/1039473?v=4" width="100px;" alt=""/><br /><sub><b>Nathan Wells</b></sub></a><br /><a href="#content-nwwells" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/paulovitin"><img src="https://avatars0.githubusercontent.com/u/125503?v=4" width="100px;" alt=""/><br /><sub><b>Paulo Reis</b></sub></a><br /><a href="#content-paulovitin" title="Content">🖋</a></td>
    <td align="center"><a href="https://snap.simpego.ch"><img src="https://avatars2.githubusercontent.com/u/1989646?v=4" width="100px;" alt=""/><br /><sub><b>syzer</b></sub></a><br /><a href="#content-syzer" title="Content">🖋</a></td>
    <td align="center"><a href="http://sancho.dev"><img src="https://avatars0.githubusercontent.com/u/3763599?v=4" width="100px;" alt=""/><br /><sub><b>David Sancho</b></sub></a><br /><a href="#content-davesnx" title="Content">🖋</a></td>
    <td align="center"><a href="https://apiforge.it"><img src="https://avatars0.githubusercontent.com/u/4929965?v=4" width="100px;" alt=""/><br /><sub><b>Robert Manolea</b></sub></a><br /><a href="#content-pupix" title="Content">🖋</a></td>
    <td align="center"><a href="https://jumptoglide.com"><img src="https://avatars2.githubusercontent.com/u/708395?v=4" width="100px;" alt=""/><br /><sub><b>Xavier Ho</b></sub></a><br /><a href="#content-spaxe" title="Content">🖋</a></td>
    <td align="center"><a href="http://www.ocular-rhythm.io"><img src="https://avatars0.githubusercontent.com/u/2738518?v=4" width="100px;" alt=""/><br /><sub><b>Aaron</b></sub></a><br /><a href="#content-ocularrhythm" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://septa97.me"><img src="https://avatars2.githubusercontent.com/u/13742634?v=4" width="100px;" alt=""/><br /><sub><b>Jan Charles Maghirang Adona</b></sub></a><br /><a href="#content-septa97" title="Content">🖋</a></td>
    <td align="center"><a href="https://www.cakeresume.com/allenfang"><img src="https://avatars2.githubusercontent.com/u/5351390?v=4" width="100px;" alt=""/><br /><sub><b>Allen</b></sub></a><br /><a href="#content-AllenFang" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/leonardovillela"><img src="https://avatars3.githubusercontent.com/u/8650543?v=4" width="100px;" alt=""/><br /><sub><b>Leonardo Villela</b></sub></a><br /><a href="#content-leonardovillela" title="Content">🖋</a></td>
    <td align="center"><a href="https://michalzalecki.com"><img src="https://avatars1.githubusercontent.com/u/3136577?v=4" width="100px;" alt=""/><br /><sub><b>Michał Załęcki</b></sub></a><br /><a href="#content-MichalZalecki" title="Content">🖋</a></td>
    <td align="center"><a href="http://www.wealthbar.com"><img src="https://avatars1.githubusercontent.com/u/156449?v=4" width="100px;" alt=""/><br /><sub><b>Chris Nicola</b></sub></a><br /><a href="#content-chrisnicola" title="Content">🖋</a></td>
    <td align="center"><a href="https://twitter.com/aecorredor"><img src="https://avatars3.githubusercontent.com/u/9114987?v=4" width="100px;" alt=""/><br /><sub><b>Alejandro Corredor</b></sub></a><br /><a href="#content-aecorredor" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/cwar"><img src="https://avatars3.githubusercontent.com/u/272843?v=4" width="100px;" alt=""/><br /><sub><b>cwar</b></sub></a><br /><a href="#content-cwar" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/keyfoxth"><img src="https://avatars3.githubusercontent.com/u/10647132?v=4" width="100px;" alt=""/><br /><sub><b>Yuwei</b></sub></a><br /><a href="#content-keyfoxth" title="Content">🖋</a></td>
    <td align="center"><a href="https://bigcodenerd.org"><img src="https://avatars3.githubusercontent.com/u/10895594?v=4" width="100px;" alt=""/><br /><sub><b>Utkarsh Bhatt</b></sub></a><br /><a href="#content-utkarshbhatt12" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/duartemendes"><img src="https://avatars2.githubusercontent.com/u/12852058?v=4" width="100px;" alt=""/><br /><sub><b>Duarte Mendes</b></sub></a><br /><a href="#content-duartemendes" title="Content">🖋</a></td>
    <td align="center"><a href="http://jasonkim.ca"><img src="https://avatars2.githubusercontent.com/u/103456?v=4" width="100px;" alt=""/><br /><sub><b>Jason Kim</b></sub></a><br /><a href="#content-serv" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/Max101"><img src="https://avatars2.githubusercontent.com/u/2124249?v=4" width="100px;" alt=""/><br /><sub><b>Mitja O.</b></sub></a><br /><a href="#content-Max101" title="Content">🖋</a></td>
    <td align="center"><a href="http://sandromiguel.com"><img src="https://avatars0.githubusercontent.com/u/6423157?v=4" width="100px;" alt=""/><br /><sub><b>Sandro Miguel Marques</b></sub></a><br /><a href="#content-SandroMiguel" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/GabeKuslansky"><img src="https://avatars3.githubusercontent.com/u/9855482?v=4" width="100px;" alt=""/><br /><sub><b>Gabe</b></sub></a><br /><a href="#content-GabeKuslansky" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://ripper234.com/"><img src="https://avatars1.githubusercontent.com/u/172282?v=4" width="100px;" alt=""/><br /><sub><b>Ron Gross</b></sub></a><br /><a href="#content-ripper234" title="Content">🖋</a></td>
    <td align="center"><a href="http://www.thecodebarbarian.com"><img src="https://avatars2.githubusercontent.com/u/1620265?v=4" width="100px;" alt=""/><br /><sub><b>Valeri Karpov</b></sub></a><br /><a href="#content-vkarpov15" title="Content">🖋</a></td>
    <td align="center"><a href="https://sergiobernal.com"><img src="https://avatars3.githubusercontent.com/u/20087388?v=4" width="100px;" alt=""/><br /><sub><b>Sergio Bernal</b></sub></a><br /><a href="#content-imsergiobernal" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/ntelkedzhiev"><img src="https://avatars2.githubusercontent.com/u/7332371?v=4" width="100px;" alt=""/><br /><sub><b>Nikola Telkedzhiev</b></sub></a><br /><a href="#content-ntelkedzhiev" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/vitordagamagodoy"><img src="https://avatars0.githubusercontent.com/u/26370059?v=4" width="100px;" alt=""/><br /><sub><b>Vitor Godoy</b></sub></a><br /><a href="#content-vitordagamagodoy" title="Content">🖋</a></td>
    <td align="center"><a href="https://www.manishsaraan.com/"><img src="https://avatars2.githubusercontent.com/u/19797340?v=4" width="100px;" alt=""/><br /><sub><b>Manish Saraan</b></sub></a><br /><a href="#content-manishsaraan" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/uronly14me"><img src="https://avatars2.githubusercontent.com/u/5186814?v=4" width="100px;" alt=""/><br /><sub><b>Sangbeom Han</b></sub></a><br /><a href="#content-uronly14me" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://blackmatch.github.io"><img src="https://avatars3.githubusercontent.com/u/12443954?v=4" width="100px;" alt=""/><br /><sub><b>blackmatch</b></sub></a><br /><a href="#content-blackmatch" title="Content">🖋</a></td>
    <td align="center"><a href="https://simmsreeve.com"><img src="https://avatars3.githubusercontent.com/u/5173131?v=4" width="100px;" alt=""/><br /><sub><b>Joe Reeve</b></sub></a><br /><a href="#content-ISNIT0" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/BusbyActual"><img src="https://avatars2.githubusercontent.com/u/14985016?v=4" width="100px;" alt=""/><br /><sub><b>Ryan Busby</b></sub></a><br /><a href="#content-BusbyActual" title="Content">🖋</a></td>
    <td align="center"><a href="http://jsdecorator.com"><img src="https://avatars3.githubusercontent.com/u/4482199?v=4" width="100px;" alt=""/><br /><sub><b>Iman Mohamadi</b></sub></a><br /><a href="#content-ImanMh" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/HeeL"><img src="https://avatars1.githubusercontent.com/u/287769?v=4" width="100px;" alt=""/><br /><sub><b>Sergii Paryzhskyi</b></sub></a><br /><a href="#content-HeeL" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/kapilepatel"><img src="https://avatars3.githubusercontent.com/u/25738473?v=4" width="100px;" alt=""/><br /><sub><b>Kapil Patel</b></sub></a><br /><a href="#content-kapilepatel" title="Content">🖋</a></td>
    <td align="center"><a href="https://twitter.com/justjavac"><img src="https://avatars1.githubusercontent.com/u/359395?v=4" width="100px;" alt=""/><br /><sub><b>迷渡</b></sub></a><br /><a href="#content-justjavac" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/hozefaj"><img src="https://avatars1.githubusercontent.com/u/2084833?v=4" width="100px;" alt=""/><br /><sub><b>Hozefa</b></sub></a><br /><a href="#content-hozefaj" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/el-ethan"><img src="https://avatars3.githubusercontent.com/u/10249884?v=4" width="100px;" alt=""/><br /><sub><b>Ethan</b></sub></a><br /><a href="#content-el-ethan" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/milkdeliver"><img src="https://avatars2.githubusercontent.com/u/3108407?v=4" width="100px;" alt=""/><br /><sub><b>Sam</b></sub></a><br /><a href="#content-milkdeliver" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/ArlindXh"><img src="https://avatars0.githubusercontent.com/u/19508764?v=4" width="100px;" alt=""/><br /><sub><b>Arlind</b></sub></a><br /><a href="#content-ArlindXh" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/ttous"><img src="https://avatars0.githubusercontent.com/u/19815440?v=4" width="100px;" alt=""/><br /><sub><b>Teddy Toussaint</b></sub></a><br /><a href="#content-ttous" title="Content">🖋</a></td>
    <td align="center"><a href="http://ardern.io"><img src="https://avatars2.githubusercontent.com/u/2419690?v=4" width="100px;" alt=""/><br /><sub><b>Lewis</b></sub></a><br /><a href="#content-LewisArdern" title="Content">🖋</a></td>
    <td align="center"><a href="https://gabriellidenor.com/"><img src="https://avatars2.githubusercontent.com/u/765963?v=4" width="100px;" alt=""/><br /><sub><b>Gabriel Lidenor </b></sub></a><br /><a href="#content-GabrielLidenor" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/animir"><img src="https://avatars3.githubusercontent.com/u/4623196?v=4" width="100px;" alt=""/><br /><sub><b>Roman</b></sub></a><br /><a href="#content-animir" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/Francozeira"><img src="https://avatars1.githubusercontent.com/u/47419763?v=4" width="100px;" alt=""/><br /><sub><b>Francozeira</b></sub></a><br /><a href="#content-Francozeira" title="Content">🖋</a></td>
    <td align="center"><a href="https://twitter.com/invvard"><img src="https://avatars0.githubusercontent.com/u/7305493?v=4" width="100px;" alt=""/><br /><sub><b>Invvard</b></sub></a><br /><a href="#content-Invvard" title="Content">🖋</a></td>
    <td align="center"><a href="https://romulogarofalo.github.io/"><img src="https://avatars1.githubusercontent.com/u/18492592?v=4" width="100px;" alt=""/><br /><sub><b>Rômulo Garofalo</b></sub></a><br /><a href="#content-romulogarofalo" title="Content">🖋</a></td>
    <td align="center"><a href="http://thoqbk.github.io/"><img src="https://avatars0.githubusercontent.com/u/1491103?v=4" width="100px;" alt=""/><br /><sub><b>Tho Q Luong</b></sub></a><br /><a href="#content-thoqbk" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/Qeneke"><img src="https://avatars2.githubusercontent.com/u/20271568?v=4" width="100px;" alt=""/><br /><sub><b>Burak Shen</b></sub></a><br /><a href="#content-Qeneke" title="Content">🖋</a></td>
    <td align="center"><a href="http://www.happy-css.com"><img src="https://avatars0.githubusercontent.com/u/2950505?v=4" width="100px;" alt=""/><br /><sub><b>Martin Muzatko</b></sub></a><br /><a href="#content-MartinMuzatko" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/autoboxer"><img src="https://avatars3.githubusercontent.com/u/2757601?v=4" width="100px;" alt=""/><br /><sub><b>Jared Collier</b></sub></a><br /><a href="#content-autoboxer" title="Content">🖋</a></td>
    <td align="center"><a href="http://hiltonmeyer.com"><img src="https://avatars3.githubusercontent.com/u/4545860?v=4" width="100px;" alt=""/><br /><sub><b>Hilton Meyer</b></sub></a><br /><a href="#content-bikingbadger" title="Content">🖋</a></td>
    <td align="center"><a href="http://kr.vuejs.org"><img src="https://avatars0.githubusercontent.com/u/1451365?v=4" width="100px;" alt=""/><br /><sub><b>ChangJoo Park(박창주)</b></sub></a><br /><a href="#content-ChangJoo-Park" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/MasahiroSakaguchi"><img src="https://avatars0.githubusercontent.com/u/16427431?v=4" width="100px;" alt=""/><br /><sub><b>Masahiro Sakaguchi</b></sub></a><br /><a href="#content-MasahiroSakaguchi" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/TheHollidayInn"><img src="https://avatars1.githubusercontent.com/u/1253400?v=4" width="100px;" alt=""/><br /><sub><b>Keith Holliday</b></sub></a><br /><a href="#content-TheHollidayInn" title="Content">🖋</a></td>
    <td align="center"><a href="https://www.coreycleary.me"><img src="https://avatars3.githubusercontent.com/u/1485356?v=4" width="100px;" alt=""/><br /><sub><b>coreyc</b></sub></a><br /><a href="#content-coreyc" title="Content">🖋</a></td>
    <td align="center"><a href="http://maxcubing.wordpress.com"><img src="https://avatars0.githubusercontent.com/u/8260834?v=4" width="100px;" alt=""/><br /><sub><b>Maximilian Berkmann</b></sub></a><br /><a href="#content-Berkmann18" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/DouglasMV"><img src="https://avatars3.githubusercontent.com/u/32845487?v=4" width="100px;" alt=""/><br /><sub><b>Douglas Mariano Valero</b></sub></a><br /><a href="#content-DouglasMV" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/marcelosdm"><img src="https://avatars0.githubusercontent.com/u/18266600?v=4" width="100px;" alt=""/><br /><sub><b>Marcelo Melo</b></sub></a><br /><a href="#content-marcelosdm" title="Content">🖋</a></td>
    <td align="center"><a href="https://twitter.com/mperk_"><img src="https://avatars0.githubusercontent.com/u/3465794?v=4" width="100px;" alt=""/><br /><sub><b>Mehmet Perk</b></sub></a><br /><a href="#content-mperk" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/ryanouyang"><img src="https://avatars2.githubusercontent.com/u/360426?v=4" width="100px;" alt=""/><br /><sub><b>ryan ouyang</b></sub></a><br /><a href="#content-ryanouyang" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/shabeer-mdy"><img src="https://avatars0.githubusercontent.com/u/26842535?v=4" width="100px;" alt=""/><br /><sub><b>Shabeer</b></sub></a><br /><a href="#content-shabeer-mdy" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/halfzebra"><img src="https://avatars1.githubusercontent.com/u/3983879?v=4" width="100px;" alt=""/><br /><sub><b>Eduard Kyvenko</b></sub></a><br /><a href="#content-halfzebra" title="Content">🖋</a></td>
    <td align="center"><a href="http://deyvisonrocha.com"><img src="https://avatars2.githubusercontent.com/u/686067?v=4" width="100px;" alt=""/><br /><sub><b>Deyvison Rocha</b></sub></a><br /><a href="#content-deyvisonrocha" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://twitter.com/georgemamer"><img src="https://avatars1.githubusercontent.com/u/20108934?v=4" width="100px;" alt=""/><br /><sub><b>George Mamer</b></sub></a><br /><a href="#content-georgem3" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/leimonio"><img src="https://avatars0.githubusercontent.com/u/1969742?v=4" width="100px;" alt=""/><br /><sub><b>Konstantinos Leimonis</b></sub></a><br /><a href="#content-leimonio" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/Zybax"><img src="https://avatars3.githubusercontent.com/u/22094453?v=4" width="100px;" alt=""/><br /><sub><b>Oliver Lluberes</b></sub></a><br /><a href="#translation-Zybax" title="Translation">🌍</a></td>
    <td align="center"><a href="https://stackoverflow.com/story/tiendq"><img src="https://avatars2.githubusercontent.com/u/815910?v=4" width="100px;" alt=""/><br /><sub><b>Tien Do</b></sub></a><br /><a href="#content-tiendq" title="Content">🖋</a></td>
    <td align="center"><a href="http://singh1114.github.io/"><img src="https://avatars0.githubusercontent.com/u/11356398?v=4" width="100px;" alt=""/><br /><sub><b>Ranvir Singh</b></sub></a><br /><a href="#content-singh1114" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/collierrgbsitisfise"><img src="https://avatars3.githubusercontent.com/u/13496126?v=4" width="100px;" alt=""/><br /><sub><b>Vadim Nicolaev</b></sub></a><br /><a href="#content-collierrgbsitisfise" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/germangamboa95"><img src="https://avatars3.githubusercontent.com/u/28633849?v=4" width="100px;" alt=""/><br /><sub><b>German Gamboa Gonzalez</b></sub></a><br /><a href="#content-germangamboa95" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/AbdelrahmanHafez"><img src="https://avatars3.githubusercontent.com/u/19984935?v=4" width="100px;" alt=""/><br /><sub><b>Hafez</b></sub></a><br /><a href="#content-AbdelrahmanHafez" title="Content">🖋</a></td>
    <td align="center"><a href="http://linkedin.com/in/chandiran-dmc"><img src="https://avatars3.githubusercontent.com/u/42678579?v=4" width="100px;" alt=""/><br /><sub><b>Chandiran</b></sub></a><br /><a href="#content-chandiran-dmc" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/VinayaSathyanarayana"><img src="https://avatars2.githubusercontent.com/u/16976677?v=4" width="100px;" alt=""/><br /><sub><b>VinayaSathyanarayana</b></sub></a><br /><a href="#content-VinayaSathyanarayana" title="Content">🖋</a></td>
    <td align="center"><a href="https://www.kimkern.de"><img src="https://avatars1.githubusercontent.com/u/2671139?v=4" width="100px;" alt=""/><br /><sub><b>Kim Kern</b></sub></a><br /><a href="#content-kiwikern" title="Content">🖋</a></td>
    <td align="center"><a href="https://kennethfreitas.github.io/"><img src="https://avatars2.githubusercontent.com/u/55669043?v=4" width="100px;" alt=""/><br /><sub><b>Kenneth Freitas</b></sub></a><br /><a href="#content-kennethfreitas" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/songe"><img src="https://avatars2.githubusercontent.com/u/1531561?v=4" width="100px;" alt=""/><br /><sub><b>songe</b></sub></a><br /><a href="#content-songe" title="Content">🖋</a></td>
    <td align="center"><a href="http://ksed.dev"><img src="https://avatars1.githubusercontent.com/u/30693707?v=4" width="100px;" alt=""/><br /><sub><b>Kirill Shekhovtsov</b></sub></a><br /><a href="#content-Ksedline" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/SerzN1"><img src="https://avatars0.githubusercontent.com/u/2534649?v=4" width="100px;" alt=""/><br /><sub><b>Serge</b></sub></a><br /><a href="#content-SerzN1" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/keyrwinz"><img src="https://avatars3.githubusercontent.com/u/21241761?v=4" width="100px;" alt=""/><br /><sub><b>keyrwinz</b></sub></a><br /><a href="#content-keyrwinz" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/nDmitry"><img src="https://avatars0.githubusercontent.com/u/2134568?v=4" width="100px;" alt=""/><br /><sub><b>Dmitry Nikitenko</b></sub></a><br /><a href="#content-nDmitry" title="Content">🖋</a></td>
    <td align="center"><a href="https://bushuai.cc"><img src="https://avatars0.githubusercontent.com/u/1875256?v=4" width="100px;" alt=""/><br /><sub><b>bushuai</b></sub></a><br /><a href="https://github.com/goldbergyoni/nodebestpractices/pulls?q=is%3Apr+reviewed-by%3Abushuai" title="Reviewed Pull Requests">👀</a> <a href="#content-bushuai" title="Content">🖋</a></td>
    <td align="center"><a href="https://stackoverflow.com/users/1348195/benjamin-gruenbaum"><img src="https://avatars2.githubusercontent.com/u/1315533?v=4" width="100px;" alt=""/><br /><sub><b>Benjamin Gruenbaum</b></sub></a><br /><a href="#content-benjamingr" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/byeze"><img src="https://avatars1.githubusercontent.com/u/7424138?v=4" width="100px;" alt=""/><br /><sub><b>Ezequiel</b></sub></a><br /><a href="#translation-byeze" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/juaoose"><img src="https://avatars3.githubusercontent.com/u/994594?v=4" width="100px;" alt=""/><br /><sub><b>Juan José Rodríguez</b></sub></a><br /><a href="#translation-juaoose" title="Translation">🌍</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/OrBin"><img src="https://avatars1.githubusercontent.com/u/6897234?v=4" width="100px;" alt=""/><br /><sub><b>Or Bin</b></sub></a><br /><a href="#content-OrBin" title="Content">🖋</a></td>
    <td align="center"><a href="https://twitter.com/andreoav07"><img src="https://avatars2.githubusercontent.com/u/508827?v=4" width="100px;" alt=""/><br /><sub><b>Andreo Vieira</b></sub></a><br /><a href="#content-andreoav" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/mikicho"><img src="https://avatars1.githubusercontent.com/u/11459632?v=4" width="100px;" alt=""/><br /><sub><b>Michael Solomon</b></sub></a><br /><a href="#content-mikicho" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/jimmycallin"><img src="https://avatars0.githubusercontent.com/u/2225828?v=4" width="100px;" alt=""/><br /><sub><b>Jimmy Callin</b></sub></a><br /><a href="#content-jimmycallin" title="Content">🖋</a></td>
    <td align="center"><a href="https://www.linkedin.com/in/siddharthofficial/"><img src="https://avatars2.githubusercontent.com/u/26025955?v=4" width="100px;" alt=""/><br /><sub><b>Siddharth</b></sub></a><br /><a href="#content-w01fS" title="Content">🖋</a></td>
    <td align="center"><a href="https://ryansmith.tech/"><img src="https://avatars0.githubusercontent.com/u/1578766?v=4" width="100px;" alt=""/><br /><sub><b>Ryan Smith</b></sub></a><br /><a href="#content-ryan3E0" title="Content">🖋</a></td>
    <td align="center"><a href="https://de.linkedin.com/in/tom-boettger"><img src="https://avatars2.githubusercontent.com/u/49961674?v=4" width="100px;" alt=""/><br /><sub><b>Tom Boettger</b></sub></a><br /><a href="#content-bttger" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/jormaechea"><img src="https://avatars3.githubusercontent.com/u/5612500?v=4" width="100px;" alt=""/><br /><sub><b>Joaquín Ormaechea</b></sub></a><br /><a href="#translation-jormaechea" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/dfrzuz"><img src="https://avatars3.githubusercontent.com/u/71859096?v=4" width="100px;" alt=""/><br /><sub><b>dfrzuz</b></sub></a><br /><a href="#translation-dfrzuz" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/victor-homyakov"><img src="https://avatars1.githubusercontent.com/u/121449?v=4" width="100px;" alt=""/><br /><sub><b>Victor Homyakov</b></sub></a><br /><a href="#content-victor-homyakov" title="Content">🖋</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->
