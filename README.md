# angular-template

This is my starter for angular application with support eslint, jest, tailwindcss out of the box. This was created when they are not supported officially then you may want to use Angular CLI to create project now.

This stater also drop Zone.js and run Angular in Zone less mode with @ngrx/component which is also under experimental.

To make your development experience like normal in Zone less mode, make sure you update your Angular Language Service to the latest version and enable `Angular: Experimental-ivy` in the settings.

Another note for anyone want to try this, you are force to use Observable for everything because without Zone.js, `ngrxLet` and `ngrxPush` is the only way for Angular Change Detector run normally.
