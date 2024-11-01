# ✨ Shiny RPC

> Minimalistic RPC standard for your microservices


[:fontawesome-brands-github: Source Code](https://github.com/OlenEnkeli/shiny-rpc-python){ .md-button }
[:fontawesome-solid-book-open: Documentation](#){ .md-button }
[:fontawesome-solid-wand-magic-sparkles: Implementations](#){ .md-button }

## 🌊 Key benefits

 - **Cross-language** - connect any services to each other.
 - **Extremely fast** - thanks for byte-coded messages.
 - **Declarative** - see `Annotation` chapter.
 - **Minimalistic** - only procedure call, nothing excess.


## 🛳 Main ideas

### 🐙 RPC

**RPC** is a acronym of **Remote Procedure Call**.

It`s means that you can call procedures on a remote server almost as easily as local functions.

### 🐠 What is it for?

The main purpose is to provide direct communication between **microservices**.

RPC is lighter and faster than, for example, the HTTP API.

### 💻 Server/Client

**Server** in this case is a separate worker which provides some procedures as entrypoints.

**Client** connected **directly** to target server. After connection, the client's methods are available to be called at any time.


### 🖋 Annotation and code generation

Declarative annotation - important part of **Quick RPC**.

Annotation is a description methods, entities, requests, responses, etc as `JSON` file.

After making annotation you can easily **generate both client and server code** on any of supported language.
