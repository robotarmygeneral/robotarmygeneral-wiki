To save changes to an object, you must save the object that is receives to its own columns.

Shell example:

  u=User.objects.get(pk=1)  
  u.userprofile.new_cards_per_day=20  
  u.save()

Result: new_cards_per_day does not change. Instead:

  up=u.userprofile  
  up.new_cards_per_day=20  
  up.save()

Weird stuff about aggregate/annotate/etc.

Debugging:
* Use Firefox's Error Console to spot Javascript errors.
* Use Firebug's console to look at responses from the server that might otherwise be hidden. Unfortunately it doesn't render the HTML, and also unfortunately, I turned off debugging on the server.
