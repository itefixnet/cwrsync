# cwRsync - Rsync client for Windows
A barebone distribution of Rsync client for Windows. That's all you need to initiate rsync requests from your computer. The rsync binary provided has following convenient patches: [transliterate](https://git.samba.org/?p=rsync-patches.git;a=blob;f=transliterate.diff;h=58b2fb26767c17ce32df08942e55159eca672676;hb=ad11a2bcb3aea2faa0c7523fbaaa42e303b0620b "Official Rsync transliterate patch"), [timelimit](https://git.samba.org/?p=rsync-patches.git;a=blob;f=time-limit.diff;h=15bf553a21dd8f2a545047ba692b8f811b369201;hb=ad11a2bcb3aea2faa0c7523fbaaa42e303b0620b "Official Rsync time-limit patch"), [ignore case](https://git.samba.org/?p=rsync-patches.git;a=blob;f=ignore-case.diff;h=3239ee66b3e415e2dd7ee812118cd1ca5ea6b0c1;hb=ad11a2bcb3aea2faa0c7523fbaaa42e303b0620b "Official Rsync ignore case patch"), [no strict check of password file permissions (unofficial)](https://github.com/RsyncProject/rsync/compare/master...itefixnet:rsync:master "How to set client side rsync password permissions ?").

![cwRsync client](https://github.com/itefixnet/cwrsync/blob/main/cwRsync_client.png)

If you need to serve rsync requests from your computer, you need to set up an rsync daemon, which we provide [as a paid solution](https://itefix.net/cwrsync/server). We do also provide an [Rsync client helper GUI](https://itefix.net/rsync-client-helper-gui) as a product.

Provided by [itefix.net](https://itefix.net)
