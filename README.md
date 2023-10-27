# Technical Interview Preparation - Round 1

## Table of Contents

- [What is Git and Github?](#q-what-is-git-and-github)
- [Difference between Git and Github?](#q-difference-between-git-and-github)
- [What are some alternatives to GitHub?](#q-what-are-some-alternatives-to-github)
- [What are cookies and sessions? Explain their difference.](#q-what-are-cookies-and-sessions-explain-their-difference)
- [What is ReactJS, and what happens when you change a state? Is it a library or framework?](#q-what-is-reactjs-and-what-happens-when-you-change-a-state-is-it-a-library-or-framework)
- [What are components in ReactJS?](#q-what-are-components-in-reactjs)
- [What is virtual DOM in React?](#q-what-is-virtual-dom-in-react)
- [What is JSX? How is JSX parsed into JavaScript?](#q-what-is-jsx-how-is-jsx-parsed-into-javascript)
- [What is the use of Webpack?](#q-what-is-the-use-of-webpack)
- [Suppose a website is very fast, and I'm willing to make it slow. What actions could be taken?](#q-suppose-a-website-is-very-fast-and-im-willing-to-make-it-slow-what-actions-could-be-taken)
- [What is CDN? How does CDN work?](#q-what-is-cdn-how-does-cdn-work)
- [What is Indexing in Database? Does Indexing affect only fetching, or does it affect insertion and updating as well?](#q-what-is-indexing-in-database-does-indexing-affect-only-fetching-or-does-it-affect-insertion-and-updating-as-well)
- [How will you move a commit from one branch to another branch?](#q-how-will-you-move-a-commit-from-one-branch-to-another-branch)
- [What does the "git stash" command do?](#q-what-does-the-git-stash-command-do)
- [Which website will be faster, the one built with JavaScript or the one built with React?](#q-which-website-will-be-faster-the-one-built-with-javascript-or-the-one-built-with-react)
- [What actions could be taken to make a website faster?](#q-what-actions-could-be-taken-to-make-a-website-faster)
- [Where is session data stored on backend servers?](#q-where-is-session-data-stored-on-backend-servers)
- [Git stores all the data in which folder?](#q-git-stores-all-the-data-in-which-folder)
- [How does the gitignore file work?](#q-how-does-the-gitignore-file-work-kindly-read-this-in-detail)
- [How to verify an email? Which is the best method to verify the email, client-based, or server-based?](#q-how-to-verify-an-email-which-is-the-best-method-to-verify-the-email-client-based-or-server-based)
- [Will the session work if we decline cookies?](#q-will-the-session-work-if-we-decline-cookies)
- [When reopening a website after closing it, the session made on that website gets destroyed automatically, and you need to log in again. Why so?](#q-when-reopening-a-website-after-closing-it-the-session-made-on-that-website-gets-destroyed-automatically-and-you-need-to-log-in-again-why-so)
- [What is GitHub's cherry-pick command?](#q-what-is-githubs-cherry-pick-command)
- [What is DOM?](#q-what-is-dom)
- [What is encryption and decryption? What is hashing? What is the purpose of salting?](#q-what-is-encryption-and-decryption-what-is-hashing-what-is-the-purpose-of-salting)
- [How does JWT work? How do symmetric and asymmetric algorithms work? What are different algorithms for encryption and hashing?](#q-how-does-jwt-work-how-do-symmetric-and-asymmetric-algorithms-work-what-are-different-algorithms-for-encryption-and-hashing)
- [Do all hashing algorithms generate a hash value of a fixed-size string of characters?](#q-do-all-hashing-algorithms-generate-a-hash-value-of-a-fixed-size-string-of-characters)
- [Can two computers have the same public IP?](#q-can-two-computers-have-the-same-public-ip)

## Additional Questions

- [How does a router assign IP addresses to computers? What happens when you hit a URL when you are connected to a router?](#q-how-does-a-router-assign-ip-addresses-to-computers-what-happens-when-you-hit-a-url-when-you-are-connected-to-a-router)
- [What if two computers connected to the same router are assigned the same IP address?](#q-what-if-two-computers-connected-to-the-same-router-are-assigned-the-same-ip-address)
- [How will you make a YouTube-like automatic video quality controller?](#q-how-will-you-make-a-youtube-like-automatic-video-quality-controller)

---

### Q-1 : What is Git and Github?

**Answer:**
Git is a version control system that allows developers to track changes to their codebase and collaborate on projects with other developers. Github is a web-based hosting service for Git repositories. It provides a platform for developers to store, share, and collaborate on code with other developers.



### Q-2 : Difference between Git and Github?

**Answer:**
Git is a version control system that allows developers to track changes to their codebase and collaborate on projects with other developers. Github is a web-based hosting service for Git repositories. While Git is a tool used for version control, Github is a platform that provides hosting for Git repositories and additional features such as issue tracking, pull requests, and code review.

### Q-3 : What are some alternatives of github??

**Answer:**
Some alternatives to Github are GitLab, Bitbucket, SourceForge, and GitKraken.

### Q-4 : What are cookies and sessions? Explain their difference?

**Answer:**
Cookies and sessions are both mechanisms used to store data on the client-side in web applications. Cookies are small text files that are stored on the client-side by the browser. They are used to store user preferences, login information, and other data that needs to persist across multiple requests. Sessions, on the other hand, are server-side storage mechanisms that store user data on the server. They are used to store sensitive data such as user authentication information and are more secure than cookies.

### Q-5 : What is ReactJS and what happens when you change a state? Is it a library or framework??

**Answer:**
ReactJS is a JavaScript library used for building user interfaces. When you change a state in React, the component re-renders and updates the view with the new state. React is a library, not a framework, because it provides a set of tools and components for building user interfaces, but it does not provide a complete solution for building web applications.

### Q-6 : What are components in reactjs?

**Answer:**
Components in ReactJS are reusable building blocks that encapsulate a piece of functionality and can be composed together to build complex user interfaces. Components can be either functional or class-based and can have their own state and lifecycle methods.

### Q-7 : What is virtual DOM in react?

**Answer:**
The virtual DOM in React is a lightweight representation of the actual DOM. It is a JavaScript object that contains all the properties and attributes of the actual DOM elements. When a component's state changes, React updates the virtual DOM, compares it with the previous version, and then updates only the parts of the actual DOM that have changed. This makes React faster and more efficient than traditional DOM manipulation.

### Q-8 : What is JSX? How JSX is parsed into Javascript??

**Answer:**
JSX is a syntax extension for JavaScript that allows developers to write HTML-like code in their JavaScript files. JSX is parsed into JavaScript using a transpiler such as Babel. The transpiler converts the JSX code into JavaScript code that can be executed by the browser.

### Q-10 : What is the use of Webpack?

**Answer:**
Webpack is a module bundler for JavaScript applications. It is used to bundle JavaScript files, CSS files, and other assets into a single file that can be served to the browser. Webpack also provides features such as code splitting, hot module replacement, and tree shaking, which help to optimize the performance of web applications.

### Q-11 : Suppose website is very fast and I'm willing to make it slow what actions could be taken?

**Answer:**
To make a website slower, you could take the following actions:
-> Increase the size of images and other media files
-> Add unnecessary JavaScript code
-> Use inefficient algorithms and data structures
-> Increase the number of HTTP requests
-> Use a slower server or hosting provider

### Q-12 : What is CDN? How CDN works?

**Answer:**
A CDN (Content Delivery Network) is a network of servers that are distributed across the globe and used to deliver content to users. When a user requests content from a website, the CDN server closest to the user's location delivers the content, which reduces the latency and improves the website's performance. CDNs work by caching content on their servers and delivering it to users from the server closest to their location.

### Q-13 : What is Indexing in Database? Do Indexing affect only fetching or it will affect insertion and updation also?

**Answer:**
Indexing in a database is a technique used to improve the performance of database queries. It involves creating a data structure that allows the database to quickly locate the data that matches a query. Indexing can affect both fetching and insertion/updation of data. While indexing can speed up fetching of data, it can also slow down insertion and updation of data because the index needs to be updated every time a new record is added or an existing record is updated.

### Q-14 : How will you move a commit from one branch to another branch?

**Answer:**
To move a commit from one branch to another branch, you can use the git cherry-pick command. First, switch to the branch where you want to apply the commit using the git checkout command. Then, use the git cherry-pick command followed by the commit hash of the commit you want to move. This will apply the commit to the current branch.

### Q-15 : What does git stash command do?

**Answer:**
The git stash command is used to temporarily save changes that are not ready to be committed. It saves the changes to a stash, which can be reapplied later using the git stash apply command.

### Q-16 : Which website will be more faster the one built with javascript or the one built with react?

**Answer:**
Both websites can be fast if they are optimized properly. JavaScript is a programming language used to build web applications, while React is a JavaScript library used to build user interfaces. React can help to improve the performance of web applications by using a virtual DOM and optimizing the rendering process, but it is not a silver bullet. The performance of a website depends on many factors such as the server, hosting provider, network latency, and the size and complexity of the application.

### Q-17 : What actions could be taken to make a website faster?

**Answer:**
To make a website faster, you could take the following actions:
Optimize images and other media files
Minimize HTTP requests
Use a content delivery network (CDN)
Minimize the use of third-party scripts and plugins
Use caching to reduce server load
Optimize the code and reduce the size of the files

### Q-18 : Where session data is get stored in backend servers?

**Answer:**
Session data is stored on the server-side in backend servers. The server generates a unique session ID for each user and stores the session data associated with that ID on the server. The session ID is then sent to the client-side as a cookie, which is used to identify the user's session on subsequent requests.

### Q-19 : Git stores all the data in which folder?

**Answer:**
Git stores all the data in a hidden folder called .git in the root directory of the repository. This folder contains all the files and metadata related to the repository, including the commit history, branches, and tags.

### Q-20 : How gitignore file works (kindly read this in detail)

**Answer:**
The .gitignore file is used to specify files and directories that should be ignored by Git. When you add a file or directory to the .gitignore file, Git will not track changes to that file or directory. This is useful for files that are generated automatically or contain sensitive information

### Q-21 : How to verify an email? Which is the best method to verify the email, client-based, or server-based?

**Answer:**
Email verification is an essential process to ensure that the email address is valid and belongs to the intended recipient. There are two methods to verify an email: client-side and server-side.

--> Client-side email verification: This method involves validating the email address on the client-side using JavaScript or other client-side scripting languages. This method is fast and provides immediate feedback to the user. However, it is not reliable as it can be bypassed by disabling JavaScript or using other tools to manipulate the input.

--> Server-side email verification: This method involves validating the email address on the server-side using programming languages such as PHP, Python, or Ruby. This method is more reliable as it cannot be bypassed by the user. However, it is slower than client-side validation as it requires a round-trip to the server.

The best method to verify an email depends on the use case. If immediate feedback is required, client-side validation is preferred. However, if reliability is the top priority, server-side validation is the way to go. There are many email verification tools available that can help with email validation. These tools use various techniques such as syntax verification, email address deduplication, catch-all server detection, and more to ensure that the email address is valid and belongs to the intended recipient. Some popular email verification tools include Emailable, ZeroBounce, Bouncer, Mailgun, and more

### Q-22 : Will the session work if we decline cookies?

**Answer:**
Sessions are a way to store user data on the server-side between requests. Cookies are a way to store user data on the client-side between requests. Sessions can use cookies to store a session ID on the client-side, which is used to identify the session on the server-side. If cookies are declined, the session ID cannot be stored on the client-side, and the session cannot be identified on subsequent requests. As a result, the session will not work if cookies are declined.

### Q-23 : When reopening a website after closing it, the session made on that website gets destroyed automatically, and you need to log in again. Why so?

**Answer:**
When a user logs in to a website, a session is created on the server-side to store user data between requests. The session ID is stored on the client-side using cookies. When the user closes the website, the session ID is lost, and the session is destroyed on the server-side. When the user reopens the website, a new session is created on the server-side, and the user needs to log in again to establish a new session. This is done for security reasons to prevent unauthorized access to the user's data.

### Q-24 : What is GitHub's cherry-pick command?

**Answer:**
The cherry-pick command is a Git command that allows you to apply a specific commit from one branch to another branch. This is useful when you want to apply a specific change from one branch to another without merging the entire branch. To use the cherry-pick command, you need to specify the commit hash of the commit you want to apply and the branch you want to apply it to. For example, the following command applies the commit with the hash "abc123" to the current branch:

`git cherry-pick abc123`

GitHub's cherry-pick command works the same way as the Git command.

### Q-25 : What is DOM?

**Answer:**
The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects, allowing programming languages such as JavaScript to interact with the page. The DOM is a hierarchical tree-like structure that represents the HTML document. Each element in the HTML document is represented as a node in the DOM tree. The DOM provides a way to access and manipulate these nodes using programming languages such as JavaScript.

### Q-26 : What is encryption and decryption? What is hashing? What is the purpose of salting?

**Answer:**
-> Encryption and decryption: Encryption is the process of converting plain text into a coded message that can only be read by authorized parties. Decryption is the process of converting the coded message back into plain text. Encryption is used to protect sensitive data from unauthorized access.
-> Hashing: Hashing is the process of converting data of any size into a fixed-size string of characters. The resulting string is unique to the input data and cannot be used to recreate the original data. Hashing is used to verify the integrity of data and to store passwords securely.
-> Salting: Salting is the process of adding a random string of characters to the input data before hashing. The purpose of salting is to make it more difficult for attackers to crack the hashed data using brute force or dictionary attacks. Salting ensures that even if two users have the same password, their hashed passwords will be different.

### Q-27 : How does JWT work? How do symmetric and asymmetric algorithms work? What are different algorithms for encryption and hashing?

**Answer:**
JSON Web Tokens (JWT) are a way to securely transmit information between parties as a JSON object. A JWT consists of three parts: a header, a payload, and a signature. The header contains information about the algorithm used to sign the token. The payload contains the data being transmitted. The signature is used to verify the authenticity of the token.

    Symmetric algorithms: Symmetric algorithms use the same key for both encryption and decryption. Examples of symmetric algorithms include AES and DES.
    Asymmetric algorithms: Asymmetric algorithms use a public key for encryption and a private key for decryption. Examples of asymmetric algorithms include RSA and ECC.

There are many algorithms for encryption and hashing, including:

    Encryption algorithms: AES, DES, RSA, Blowfish, Twofish, and more.
    Hashing algorithms: MD5, SHA-1, SHA-2, SHA-3, and more.

### Q-28 : Do all hashing algorithms generate a hash value of a fixed-size string of characters?

**Answer:**
No, not all hashing algorithms generate a hash value of a fixed-size string of characters. Some hashing algorithms, such as MD5 and SHA-1, generate a fixed-size hash value. Other hashing algorithms, such as SHA-256 and SHA-512, generate a hash value of variable length.

### Q-29 : Can two computers have the same public IP?

**Answer:**
Yes, two computers can have the same public IP address if they are connected to the same network. A public IP address is assigned to a network, not to a specific computer. All devices on the same network share the same public IP address. However, each device on the network has a unique private IP address that is used to identify it on the network.

### Q-30 : How does a router assign IP addresses to computers? What happens when you hit a URL when you are connected to a router?

**Answer:**
A router assigns IP addresses to computers using a protocol called Dynamic Host Configuration Protocol (DHCP). When a computer connects to a network, it sends a DHCP request to the router, which assigns it a unique IP address. The router also assigns other network settings, such as the subnet mask and default gateway. When you hit a URL when you are connected to a router, the request is sent to the router, which forwards it to the appropriate device on the network. The device responds to the request, and the response is sent

### Q-31 : What if two computers connected to the same router are assigned the same IP address?

**Answer:**
If two computers connected to the same router are assigned the same IP address, it can cause network issues and communication problems. The router uses the IP address to identify each device on the network, and if two devices have the same IP address, the router cannot distinguish between them. This can cause data packets to be sent to the wrong device or not be delivered at all. The most common cause of IP address conflicts is when a network administrator manually configures IP addresses for devices using static IP allocation. This can lead to two devices being configured with the same IP address. Using inefficient IP address management solutions like spreadsheets for IP management can lead to this issue. Employing both static and dynamic IP address allocation to configure IP addresses for network devices can also lead to IP conflicts.

### Q-32 : How will you make a YouTube-like automatic video quality controller?

**Answer:**
To make a YouTube-like automatic video quality controller, you can follow these steps:
    --> Determine the user's internet speed: You can use JavaScript to determine the user's internet speed by measuring the time it takes to download a small file from the server.
    Determine the available video qualities: You can use the YouTube API to determine the available video qualities for the video.
    --> Select the appropriate video quality: Based on the user's internet speed and the available video qualities, you can select the appropriate video quality to ensure smooth playback without buffering.
    --> Change the video quality dynamically: You can use JavaScript to change the video quality dynamically based on the user's internet speed. For example, if the user's internet speed drops, you can switch to a lower video quality to prevent buffering.
    --> Provide a manual override: You can provide a manual override option for users who want to select a specific video quality.
    --> Test and optimize: You can test the video quality controller on different devices and internet speeds to ensure that it works as expected. You can also optimize the controller to ensure that it provides the best possible user experience.
YouTube uses a similar approach to automatically adjust the video quality based on the user's internet speed. They use a combination of adaptive streaming and video codecs to ensure smooth playback without buffering
