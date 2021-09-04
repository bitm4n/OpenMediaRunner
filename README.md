# OPEN MEDIA RUNNER

Open Media Runner (OMR) is a descentralized application (dAPP), currently in development, aimed at implementing a privacy-centric, censorship-resistant, decentralized, and cost-effective, marketplace for multimedia content creators and consumers.

OMR will be built on top of modern descentralized technologies and open source software, such as blockchain-based cryptocurrencies, P2P file transfer networks, instant messaging (IM) protocols, etc. OMR will be designed following the UNIX philosophy, that is, OMR is devised to be developed in a modular fashion, where a set of plugins perform different tasks required to achieve the final goal.

Currently, the following components have been considered to be the backbone of OMR:

* A graphical user interface (GUI) client app, meant for consumers, that will allow them to explore stores and content for sale.

* A plugin to fetch encrypted content from a diverse array of online sources, such as file hosting servers, P2P networks, and distributed file systems.

* A set of plugins that perform invoice generation for different cryptocurrencies.

* A module that request confirmation to a _payment processor server_ via a IM protocol.

* A _payment processor_ system that validates blockchain transactions and delivers keys to decrypt the requested content.


<p align="center">
  <img src="https://github.com/bitm4n/OpenMediaRunner/blob/main/design.png" alt="preview"/>
</p>
OMR proposed architecture, by b1tm4n (icons artwork by Elementary team[2]).

## Proposed usage example

1. User launches OMR GUI client app, and opens a "store sources" file that specifies where store content can be fetched.

2. Files that make up the store front are downloaded and... 

3. Loaded into the GUI client app, so a store is displayed on the GUI app, and the user can explore available content for sale.

4. User can download encrypted content for sale right away.

5. User request an invoice to purchase some content. 

6. User makes payment using (external/third party) crypto wallet.

7. User confirms payment in the GUI client app.

8. OMR client app connects to remote _payment processor_ server to validate blockchain transaction.

9. Payment processor server confirms transaction and delivers keys to decrypt purchased content.

OMR architecture is designed to be privacy centric (by using cryptocurrencies as form of payment) and censorship resistant, such that if content is removed from current source, an updated, _store sources_ file can be reloaded into the client app, with new links directing to migrated content. Store sources file can be a small file, easily distributable via social media platforms.

## Development Stage

As of Sept 3rd 2021

- Planning - Analysis

## Authors

* **B1tm4n** - [bitm4n](https://github.com/bitm4n)


## License

OMR is going to be free (as in speech) software.

## Changelog

First commit. 

- Proposed design. 

## Manifiesto

_“20 years ago, we had decentralized Internet and a relatively unrestricted banking system. Today, Apple and Google censor information and apps on our phones, while Visa and Mastercard limit what goods and services we can pay for. Every year, we give up more power and control over our lives to a handful of unaccountable corporate executives we didn’t elect.”_ - Pavel Durov[1]

OMR is meant to open a new front on the fight for a decentralized, democratic, and private, Internet.

# CONTRIBUTORS WELCOMED - HELP WANTED

## References

[1] https://www.rt.com/russia/533524-durov-google-censorship-blame/

[2] https://github.com/elementary/icons

