# ParQuik

ParQuik is a smart parking ecosystem that is revolutionizing the way we approach parking, making it more efficient and user-friendly. It addresses the common parking challenges that we all face, such as congestion, inefficient space usage, and complex payment processes. ParQuik provides a smart parking solution that streamlines the entire process, making parking more convenient and hassle-free for everyone involved.

## The Current Problem
Congestion: Parking lots are often congested, making it difficult to find a spot, especially during peak hours.

Inefficient space usage: Parking lots are often inefficiently used, with empty spaces scattered throughout.

Complex payment processes: Manual payment processes can be time-consuming and cumbersome.

![Problem Statistics](https://github.com/Adip-KG/ParQuik/assets/87146827/e6dca155-68db-4157-b453-148769d55e97)

## System Architecture
ParQuik's system architecture is comprised of the following components:
1. User registration on ParQuik is simple and straightforward. Users can register on the ParQuik platform using their email address or mobile phone number. Once registered, users can generate a unique QR code that serves as their entry ticket.

2. Vehicle entry with ParQuik is hassle-free. Users simply need to scan their QR code at the entry gate. The system will verify their identity and confirm their parking duration. Once verified, the entry gate will open automatically.

3. ParQuik employs a sophisticated allocation algorithm that optimizes parking assignments. A computer vision module uses object detection to differentiate between vacant and occupied parking slots. An abstract and simplified version of the same is displayed to the user, enabling them to choose their parking slot.
<img width="1089" alt="image" src="https://github.com/Adip-KG/ParQuik/assets/87146827/f77198a2-d503-4618-b217-a20c1b8658bd">

4. Users can choose from various payment methods within the ParQuik app, including credit/debit cards and mobile payment apps. The system calculates parking fees based on the duration of the stay and vehicle type. Real-time duration tracking eliminates the need for manual timekeeping and reduces disputes.

5. Exiting the parking lot with ParQuik is straightforward. Users simply need to scan the same QR code that was generated during entry. This process verifies their identity and confirms their parking duration. The exit gate opens automatically, ensuring minimal wait times and reducing congestion.

## Benefits of our Solution
ParQuik offers a number of benefits, including:

Reduced congestion: ParQuik's efficient parking space allocation algorithm reduces congestion and makes it easier for drivers to find a spot.

Enhanced parking efficiency: ParQuik streamlines the entire parking process, from entry to payment to exit. This makes parking more efficient and convenient for everyone involved.

Improved user experience: ParQuik's user-friendly interfaces and efficient parking process make the overall parking experience more pleasant and hassle-free for users.

Economic and environmental benefits: ParQuik's efficient use of parking space can lead to economic and environmental benefits.

## Technology Stack
**Frontend**
Flutter - App Development
Figma - UI/UX

**Backend** Python 

_Conventional Libraries_
QR - QR Generation
Pickle - Image Analysis

_Machine Learning Libraries_
OpenCV - Computer Vision
CVzone - Object Detection

**Database**
Google Firebase
