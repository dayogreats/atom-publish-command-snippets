# atom-publish-command-snippets
Quick command snippets for publishing Atom Package.


#### Steps to create and publish atom package/ theme

  * command-shift-P > Package > Package Generator: Generate Syntax Theme > mypackage

  * cd ~/.atom/packages/mypackage

  * apm login

  * apm develop mypackage

  * cd ~/github/mypackage

  * sudo chown -R username:wheel .

  *  git commit -a -m 'checking everything in'

  *  apm publish --tag v2.5.0 minor

  * apm publish minor

  * apm publish major
