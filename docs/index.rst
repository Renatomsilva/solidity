Solidity
========

.. image:: logo.svg
    :width: 120px
    :alt: Solidity logo
    :align: center

Solidity é uma linguagem de alto nível para implementação de smart contracts.
Ela foi influenciada por C++, Pythom e JavaScript e feita para rodar na Ethereum Virtual Machine (EVM).

Solidity é estaticamente tipada, suporta herança, bibliotecas e 
tipos complexos definidos pelo usuário entre outros recursos.

Como você verá, é possível criar contratos para a votação,
crowdfunding, leilões, carteiras multi-assinatura e muito mais.

.. note::
    A melhor maneira de experimentar a Solidity agora é usando o
    `Remix <https://remix.ethereum.org/>`_
    (Pode levar algum tempo para carregar, seja paciente).

Tradução
--------

Esta documentação é traduzida em vários idiomas por voluntários da comunidade, mas a versão em inglês é a principal referência.

* `Spanish <https://solidity-es.readthedocs.io>`_
* `Russian <https://github.com/ethereum/wiki/wiki/%5BRussian%5D-%D0%A0%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%BF%D0%BE-Solidity>`_ (rather outdated)
* `Portugues Brazil <https://solidity-docs-prbr.readthedocs.io>`_

Links úteis
------------

* `Ethereum <https://ethereum.org>`_

* `Changelog <https://github.com/ethereum/solidity/blob/develop/Changelog.md>`_

* `Story Backlog <https://www.pivotaltracker.com/n/projects/1189488>`_

* `Source Code <https://github.com/ethereum/solidity/>`_

* `Ethereum Stackexchange <https://ethereum.stackexchange.com/>`_

* `Gitter Chat <https://gitter.im/ethereum/solidity/>`_

Available Solidity Integrations
-------------------------------

* `Remix <https://remix.ethereum.org/>`_
    Browser-based IDE with integrated compiler and Solidity runtime environment without server-side components.

* `IntelliJ IDEA plugin <https://plugins.jetbrains.com/plugin/9475-intellij-solidity>`_
    Solidity plugin for IntelliJ IDEA (and all other JetBrains IDEs)

* `Visual Studio Extension <https://visualstudiogallery.msdn.microsoft.com/96221853-33c4-4531-bdd5-d2ea5acc4799/>`_
    Solidity plugin for Microsoft Visual Studio that includes the Solidity compiler.

* `Package for SublimeText — Solidity language syntax <https://packagecontrol.io/packages/Ethereum/>`_
    Solidity syntax highlighting for SublimeText editor.

* `Etheratom <https://github.com/0mkara/etheratom>`_
    Plugin for the Atom editor that features syntax highlighting, compilation and a runtime environment (Backend node & VM compatible).

* `Atom Solidity Linter <https://atom.io/packages/linter-solidity>`_
    Plugin for the Atom editor that provides Solidity linting.

* `Atom Solium Linter <https://atom.io/packages/linter-solium>`_
    Configurable Solidty linter for Atom using Solium as a base.

* `Solium <https://github.com/duaraghav8/Solium/>`_
    A commandline linter for Solidity which strictly follows the rules prescribed by the `Solidity Style Guide <http://solidity.readthedocs.io/en/latest/style-guide.html>`_.
    
* `Solhint <https://github.com/protofire/solhint>`_
    Solidity linter that provides security, style guide and best practice rules for smart contract validation.

* `Visual Studio Code extension <http://juan.blanco.ws/solidity-contracts-in-visual-studio-code/>`_
    Solidity plugin for Microsoft Visual Studio Code that includes syntax highlighting and the Solidity compiler.

* `Emacs Solidity <https://github.com/ethereum/emacs-solidity/>`_
    Plugin for the Emacs editor providing syntax highlighting and compilation error reporting.

* `Vim Solidity <https://github.com/tomlion/vim-solidity/>`_
    Plugin for the Vim editor providing syntax highlighting.

* `Vim Syntastic <https://github.com/scrooloose/syntastic>`_
    Plugin for the Vim editor providing compile checking.

Discontinued:

* `Mix IDE <https://github.com/ethereum/mix/>`_
    Qt based IDE for designing, debugging and testing solidity smart contracts.

* `Ethereum Studio <https://live.ether.camp/>`_		
    Specialized web IDE that also provides shell access to a complete Ethereum environment.

Solidity Tools
--------------

* `Dapp <https://dapp.readthedocs.io>`_
    Build tool, package manager, and deployment assistant for Solidity.

* `Solidity REPL <https://github.com/raineorshine/solidity-repl>`_
    Try Solidity instantly with a command-line Solidity console.

* `solgraph <https://github.com/raineorshine/solgraph>`_
    Visualize Solidity control flow and highlight potential security vulnerabilities.

* `evmdis <https://github.com/Arachnid/evmdis>`_
    EVM Disassembler that performs static analysis on the bytecode to provide a higher level of abstraction than raw EVM operations.

* `Doxity <https://github.com/DigixGlobal/doxity>`_
    Documentation Generator for Solidity.

Third-Party Solidity Parsers and Grammars
-----------------------------------------

* `solidity-parser <https://github.com/ConsenSys/solidity-parser>`_
    Solidity parser for JavaScript

* `Solidity Grammar for ANTLR 4 <https://github.com/federicobond/solidity-antlr4>`_
    Solidity grammar for the ANTLR 4 parser generator

Documentação da Linguagem
-------------------------

Nas proximas páginas, primeiro veremos um :ref:`simples smart contract <simple-smart-contract>` escrito em Solidity seguido pelo básico sobre :ref:`blockchains <blockchain-basics>`
e :ref:`Ethereum Virtual Machine <the-ethereum-virtual-machine>`.

A próxima seção explicara várias *features* do Solidity e suas vantagens :ref:`contrato exemplo <voting>`
Lembre-se você pode testar seus contractos
`no seu navegador <https://remix.ethereum.org>`_!

A última e mais extensa seção abordará todos os aspectos da Solidity em profundidade.

If you still have questions, you can try searching or asking on the
`Ethereum Stackexchange <https://ethereum.stackexchange.com/>`_
site, or come to our `gitter channel <https://gitter.im/ethereum/solidity/>`_.
Ideas for improving Solidity or this documentation are always welcome!

Contents
========

:ref:`Keyword Index <genindex>`, :ref:`Search Page <search>`

.. toctree::
   :maxdepth: 2

   introduction-to-smart-contracts.rst
   installing-solidity.rst
   solidity-by-example.rst
   solidity-in-depth.rst
   security-considerations.rst
   using-the-compiler.rst
   metadata.rst
   abi-spec.rst
   julia.rst
   style-guide.rst
   common-patterns.rst
   bugs.rst
   contributing.rst
   frequently-asked-questions.rst
