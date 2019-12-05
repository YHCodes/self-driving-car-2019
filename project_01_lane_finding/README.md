
检测车道线基本版本, 主要步骤:
1. use `cv2.GaussianBlur()` to blur image
2. use `cv2.Canny()` to detect edges
3. get region of interest 
4. use `cv2.HoughLinesP()` to detect lines
5. `cv2.addWeighted()` combine image
