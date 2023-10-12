## [Project 10: Names to Faces](https://www.hackingwithswift.com/read/10/overview)
Written by [Paul Hudson](https://www.hackingwithswift.com/about)  ![twitter16](https://github.com/juliangyurov/PH-Project6a/assets/13259596/445c8ea0-65c4-4dba-8e1f-3f2750f0ef51)
  [@twostraws](https://twitter.com/twostraws)

**Description:** Get started with `UICollectionView` and the photo library.

- Setting up

- Designing `UICollectionView` cells

- `UICollectionView` data sources

- Importing photos with `UIImagePickerController`

- Custom subclasses of `NSObject`

- Connecting up the people

- Wrap up

 ## [Review what you learned](https://www.hackingwithswift.com/review/hws/project-10-names-to-faces)

**Challenge**

1. Add a second `UIAlertController` that gets shown when the user taps a picture, asking them whether they want to rename the person or delete them.

2. Try using `picker.sourceType = .camera` when creating your image picker, which will tell it to create a new image by taking a photo. This is only available on devices (not on the simulator) so you might want to check the return value of `UIImagePickerController.isSourceTypeAvailable()` before trying to use it!

3. Modify Project1 so that it uses a collection view controller rather than a table view controller. I recommend you keep a copy of your original table view controller code so you can refer back to it later on.
