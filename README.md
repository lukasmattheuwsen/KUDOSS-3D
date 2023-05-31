# KUDOSS-3D: KU Leuven Dataset for Outdoor Semantic Segmentation on 3D point cloud data

![Image](screenshots/dataset_RGB_label_horo.png)

KUDOSS-3D is a large-scale benchmark dataset for semantic segmentation of 3D point cloud data of outdoor scenes. The dataset contains 76,8 million points of a 2.5 km residential neighbourhood spanning a 300 meter by 400 meter area. 

![Image](screenshots/Picture5.png)

The dataset contains the following attributes:
* **XYZ**
* **RGB**
* **Intensity**
* **Groung truth class**
  * **Class 1 Road**: Drivable areas where cars are allowed, including service lanes, bikes lanes if not elevated with respect to the road surface.
  * **Class 2 Parking/sidewalk**: Includes areas used for parking cars or vehicles which are clearly separated from the road surface by a small curb or gutter. This also includes the driveways of private properties. Also included are the sidewalks which are elevated by curbs from the road surface.
  * **Class 3 Natural terrain**: Grass or soil surfaces
  * **Class 4 Low vegetation**: Small bushes, flower beds, and other clearly identifiable vegetation lower than 2 meters.
  * **Class 5 High vegetation**: Trees ans larger bushes taller than 2 meters. A large bush over 2 meters is labeled completely as high vegetation rather than splitting it in low and high vegetation.
  * **Class 6 Buildings**: Houses, churches, stores, garages.
  * **Class 7 Hardscape**: Overarching class of man-made structures such as walls, fences, benches, poles, mail boxes.
  * **Class 8 Cars/vehicle**: All motor vehicles moving or stationary.
  * **Class 9 Scanning artifacts**: Ghost or noise points caused by dynamic or reflective objects. This also includes fast moving cars which are not clearly identifiable. 
  * **Class 10 Unclassified**

## <a name="download"></a> Download dataset
Dataset can be downloaded at [OneDrive](https://kuleuven-my.sharepoint.com/:f:/g/personal/lukas_mattheuwsen_kuleuven_be/EkXzHZTIOlBLgOJvk3tUhQsBmu7D90eFpSejS6js1GiaqQ?e=38nK5Y)
