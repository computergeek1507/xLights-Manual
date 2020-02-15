# Model Groups

## Model Groups

A Model Group defines a collection of models. It is an optional entity, but very useful, in that many effects can be sequenced against the Model Group and xLights will then generate effects on all the Models in the group.

A Model can belong to more than one Model Group. An an example a model ‘Arch1’ can belong to the ‘All Models Group’ Model group as well as the ‘Arches Group’

You can also have models that do not belong to a Model Group - for example a matrix that you wish to sequence effects on separately such that dropping an effect on the” All Models” group does not affect the matrix.

To create a Model Group, from the layout tab right click within the Model list window. Click on Add Group, enter a Model Group name in the resultant window and click Ok.

![](../../.gitbook/assets/image%20%28211%29.png)

In the layout windows, a Model Group can be added by highlight multiple models, right click, and select 'Create Group'.

![](../../.gitbook/assets/image%20%2817%29.png)

In xLights, Model Groups are sequenced against an internal grid representation.

The Default Layout Mode and Max Grid Size provides options on how the ‘internal grid’ is to be calculated when effects run across a model group.

![](https://lh3.googleusercontent.com/fBfOYue0AOA_lFWxQqvFFETJdwYlDIHqzfcoDelNa-NJub1nkdL9vmFLTA08DHFJSi097h9kDrGlsYueHM5d2IuspjUyI1eesQ4P2SXq4Jc_mPQT2lofsR0g4YMXI3PehU7pspyr)

If ‘Grid as per preview’ is selected , then the buffer used will be exactly as to how the the house preview appears i.e will be quite large.

If ‘Minimal Grid’ is selected then the buffer area will be an area just surrounding the model group.

{% hint style="success" %}
Select minimal grid wherever you can. Large grid sizes can significantly slow down rendering, particularly on some effects like fan and shockwave.
{% endhint %}

To modify the models that form part of a group, click on the group name.

The models that are currently in the group will be displayed in the ‘Models in Group’ right list and the other models will be displayed in the ‘Add to Group’ left list. Use the arrows to add or remove models as required and click on the Save when done.

{% hint style="info" %}
The order of the models in the ‘Models in Group’ determines the render order of the Group Render Styles. 'Per Model' group render styles are rendered in model order top to bottom.
{% endhint %}

![](../../.gitbook/assets/image%20%28515%29.png)

To remove a Model Group, select the Model Group from the model list, right click and select Delete Group. This will not change or remove any of the underlying models, however any effects that have been placed at that group level on the sequencer will be removed and the Model group will be removed from the Layout display if it has been added to that display.

To rename a Model Group, select the Model Group from the same list , right click and select Rename Group. Enter the new name for the Model Group. 'Clone Group' will create a copy of the current group with the same models. 'Delete Empty Groups' will delete Model Group with containing no models.

{% hint style="info" %}
Selecting a Model Group from the list, sets it as a filter and only that Model Group is active on the layout; as such only models that are part of that group are displayed on the Preview screen. In order to revert back to all the models , Click on the ‘eye’ next to the Model Group name to deselect it.
{% endhint %}

If the ‘Overlap checks enabled’ attribute is selected, when you click on the model name in the list, it will turn yellow in the layout display to the right. If there is a channel overlap with any other model, then the other model will turn red.

If you hover on a model name, it will display details of the setup configuration such as the names and channel assignments the model maps to on your controller setup.

{% hint style="success" %}
It is useful to have a Model Group \(say “All Models”\) and include all the models for your show and include that model group on the layout tab.
{% endhint %}

