To fully utilize VISSET in the Robotics lab, keep it organized, clean, and orderly. Please strictly follow this convention.

# Asset
Asset in VISSET are anything that have an **asset tag**. Asset tags are a unique identifier for assets within system. Each one must be unique, and is often used in conjunction with Asset Labels. They identify each unique piece of hardware so that you know which specific device it is. 

## Categories
Categories describe the general type of asset. In current setting (29/05/2024), our lab's assets are categorized into 9 types (can be added in the future).

- Accessory
- Camera
- Computer
- Drone	
- Electronics
- Monitor
- Motor
- Robot	
- Sensor

Categories are important because they contain attributes that are inherited by assets that belong to them, such as whether to email the end-user when an item has been checked out to them, whether to require the user to click on a link to show that they have received the asset or accessory, and whether or not the user should be emailed a EULA.

Every asset needs to belong to a category, so you’ll need to set these up before adding assets.

## Asset Model
Asset model can be things like the sub-category of a Computer (SBC - Single Board Computer, for example). When you create new assets, you’ll select whichever asset model makes sense.

Asset models are important because they carry certain attributes which are inherited by the assets you create, such as depreciation type, end of life, and whether or not to show MAC address fields on the asset.

## Asset Model NO.
Asset model NO. is a specific type of asset. Where you 

These are example of fully described asset.

- Categories - Computer
- Asset Model - SBC
- Asset Model NO. - RaspberryPI 5
- Asset Tag - 00000435

## BYOD (Bring Your Own Device)
In original usecase (SnipeIT), this property allows you to notice that this device is brought by your own. However, in VISSET you can utilize this property to easier track student grant asset. 


## Status labels
- Deployable - This asset is freely use.
- Deployed (follow by owner) - This asset is checkout.
- Delivered - This asset cannot be used, due to sending out to other company.
- Broken - This assest cannot be used, need to fix.
- Missed - This assset cannot be used, and no longer can track where it is.