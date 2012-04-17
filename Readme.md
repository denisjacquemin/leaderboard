
# Meteorjs example - Leaderboard

  A live-updating high score list ([Documentation](http://meteor.com/examples/leaderboard))

## Exercice 1

Make a button that toggles between sorting by score and sorting by name. Hint: use a Session variable to hold the current sort choice.

I faced the following issues
  * Event maps with selectors won't match top-level elements in a template
  * Events handlers must be defined in one unique block, otherwise only the last block is taken into account
    