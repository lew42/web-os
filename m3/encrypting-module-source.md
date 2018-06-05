# Module source code encryption

The most immediate problem with monetizing open source code, is the most obvious:  the code is public.  Why would anyone pay for something that they can freely copy and paste?

Imagine you could import an `npm` module, without being able to actually see the source code.

Why?  So that you could monetize a secret 1-line formula, for example, without fear that the end user can rip off your secret.

This introduces a new problem:  how do you stop malicious code, if you can't see it?  How can I trust your "secret module" if I can't see its source code?

We have a simple model for solving this problem:  requesting/granting access permissions, such as with mobile apps.  Does a module need access to the `fs`?  Can the module make network requests?

## One minor hurdle:  Malicious Code

If the source code is encrypted, you don't know what it's doing.  With `npm`, a module author could decide, overnight, to publish a new change that reads your file system and steals personal information.

Yet, if each module is sandboxed as securely as possible, each module would need to require access to use the file system, and would be sandboxed to its own directory (I believe most operating systems do this by default?).

Allowing arbitrary code to run in a safe, sandboxed environment is a tricky, but important challenge to solve.
