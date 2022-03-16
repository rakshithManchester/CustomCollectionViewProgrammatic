# Creating Custom CollectionView Programmatically using 'UICollectionViewController'.
1) UI configuration for Custom Navigation bar header:



Build errors:
1) 'UICollectionView must be initialized with a non-nil layout parameter'
    
Initialise UICollectionViewFlowLayout when UIViewController instance is created.Ex: let viewController = UIViewController(collectionViewLayout: UICollectionViewFlowLayout())

  
