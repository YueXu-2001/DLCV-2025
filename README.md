# DLCV-2025

# Dataset Cleanup Summary

I have deleted some JSON files because they contained incomplete data entries.

## JSON File Structure

Each JSON file contains the following fields with specific categorical values:

- **`Outfit_Gender`**:  
  - Possible values: `{'female', 'male', 'unisex'}`

- **`Outfit_Occasion`**:  
  - Possible values: `{'Campus', 'Dating', 'Home', 'Party', 'Sports', 'Travel', 'Wedding', 'Workplace'}`

- **`Outfit_Style`**:  
  - Possible values:  
    ```
    {
      'Artistic', 'Bohemian', 'British', 'Business', 'Casual', 'Elegant', 'Girly', 'Hip-hop', 'Japanese', 
      'Korean', 'Motorcycle', 'Sexy', 'Simple', 'Sporty', 'Western', 'college', 'dark', 'ethnic', 'fresh', 
      'frigid', 'neutral', 'punk', 'retro', 'socialite', 'sweet'
    }
    ```

- **`Category`**:  
  - Possible values: `{'Bags', 'Pants', 'Shoes', 'Skirt', 'Top'}`

- **`Subcategory`**:  
  - Possible values:  
    ```
    {
      'Boots', 'backpacks', 'briefcase', 'business casual shoes', 'cardigans', 'computer bag', 
      'dress pants', 'formal shoes', 'polo shirts', 'sandals', 'shoulder/crossbody bag', 'sneakers', 
      'sports shoes', 'suits', 'sweaters', 'vests', 'work shoes', 'Bean shoes', 'Bell-bottom pants', 
      'Bucket bag', 'Chelsea boots', 'Fish-mouth shoes', 'High heels', 'Jumpsuit', 'Martin boots', 
      'Sandals', 'Shoulder bag', 'Tote bag', 'Wallet', 'ankle boots', 'backpack', 'boots', 
      'bottoming shirt', 'canvas bag', 'cardigan', 'chain bag', 'chiffon shirt', 'crossbody bag', 
      'dress', 'handbag', 'hands bag', 'loafers', 'mules', 'overalls', 'platform shoes', 'roman shoes', 
      'shell bag', 'shoes', 'skirt', 'square bag', 'suit', 'sweater', 'vest', 'wedge shoes', 'wide-leg pants'
    }
    ```

---


