# critique
An ANN designed to work out what music tastes a user has to create smart recommendations.

## Premise
Uses spotify playlists to create a set of training data which is fed into a recurrent convolutional neural network.

Reasons:
*   Recurrent: Needs to work for songs of varying length
*   Convolutional: Music is typically pattern based, if it can work out patterns I like, it should work well

## Future aspirations
Use this ANN as the trainer for another ANN which attempts to make 'good' music, based on what this project considers good.
