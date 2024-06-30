### Inspiration

Our app was inspired by a challenge faced by our team member Veronika while sewing a pair of pants. She had to print numerous pattern pieces and glue them together, which was both time-consuming and cumbersome. This sparked the idea for a tool to streamline the process using mixed reality to replace physical patterns with virtual ones. Jennie's mother, an avid seamstress, further fueled our inspiration by providing us with a PDF of a t-shirt pattern. We found that even a simple t-shirt required around 30 pages of printed patterns. Cutting out these patterns and gluing them together took Luisa and Moritz about 20 minutes, with the biggest challenge being aligning the pieces correctly to avoid mistakes and wasted paper.

### What It Does

Our app functions as a virtual sewing assistant, guiding users—especially those new to sewing—through the entire process. The core concept is to accelerate the sewing process by using virtual patterns instead of printed ones. These virtual patterns can be directly traced, streamlining the workflow and saving valuable time. To provide users with a spatial view of their clothing projects, we implemented a 3D model that visually represents the final product. Users can interact with the 3D model to extract different parts of the pattern, which transform into 2D patterns similar to a UV unwrapping process. These 2D patterns can be placed on fabric, allowing users to trace and cut with ease.

### Technologies We Used

We utilized the Meta Quest 3 and the Meta MixedReality Toolkit, incorporating features like Passthrough and HandTracking. We also implemented the Meta MixedReality Utility Kit for spatial room understanding to anchor content, as well as the Meta DepthAPI for a more realistic experience. Additional tools included Blender, Figma, Capcut, and more.

### How We Built It

We developed the application using the Unity Game Engine in combination with various development kits and libraries, ensuring it runs smoothly on the Meta Quest 3.

### Challenges We Ran Into

Our team had limited experience with the newest version of the Meta SDK and developing for the Meta Quest 3. We had to familiarize ourselves with the building blocks and their functionalities. Another challenge was creating a smooth transition between the spatial t-shirt part and the equivalent pattern while the user held it. We integrated a particle effect to enhance this process. Additionally, snapping the virtual patterns to the surface of the table was problematic; the hand tracking and utility building blocks of Meta didn't work correctly, so we wrote a custom script and implemented the snapping function ourselves.

### Accomplishments That We Are Proud Of

We are proud of integrating newly added features like the Meta Utility Kit into our project, translating our vision into a working application. We also iteratively improved the user experience, which was very important to us but also time-consuming.

### What We Learned

We learned to implement and customize the building blocks based on the needs of our use case.

### What's Next for Stitch

In the next iteration, we plan to implement a feature that allows users to load their patterns via the internet, further enhancing the app's functionality and convenience.
