# Render All

## Render All

![](../../.gitbook/assets/image%20%28641%29.png)

The ‘Render All’ function is used to force a render of all effects - that have either been created within xLights, imported via the Import Effects function or has been imported as a Data layer.

### Rendering order

The Data Layer order renders from the bottom to top. Therefore what is on the top layer will be done last – much like painting – the last brush strokes are on the top.

![](https://lh5.googleusercontent.com/1RzP8lBxdakPtz4z5UzqFi1ZJtAsjga6ljhSnCE_QgOB_Wd-78uE5gaAqW8b2Gn_OV0RS7O4esmern6jZzsQ6rWKI1kkQfO2JNycupM24z0_imAP4BfrnaJpouEP-5q6BqOYk2sP)

Model layers also render from the bottom to top. Therefore the bottom layer will be rendered first, then the layer above it and do on until the top layer is rendered last.

However, the Models themselves render top to bottom based on how they are laid out in the Master View of the sequence. So the top model is rendered first, then the next lower model until the last model is reached.

This is important to keep in mind when you have multiple models or model groups mapped to the same channels such as whole house model group and regular models.

{% hint style="success" %}
You can change the order of data layer by moving them up or down. You can similarly change the order of layers within a model. And you can also change the order of models in the master view.
{% endhint %}

{% hint style="success" %}
Always put your large groups at the top. To view your rendering order you need to be in the Master View and it renders top to bottom. Use the display elements window to change the ordering. Set the render order in the Master View and then use all my other views for sequencing. All other views don't affect rendering order they are for display purposes only.
{% endhint %}

