<h1>Lab-11-Async-Inn</h1> 

### Project Name: Async Inn Hotel Asset Management System

### Author:Bashar Shehadeh
### Date: 7/16/2023

<hr>

<h2>Description</h2>
<h4>The Async Inn Hotel Asset Management System is a web-based API designed to help Async Inn, a local hotel chain, better manage their hotel assets across multiple locations.
  This project aims to provide a RESTful API server that allows the management of rooms, amenities, and new hotel locations.
  The system leverages a relational database to store and maintain the integrity of the data.</h4>

  <hr>
  <h2>ERD Diagram</h2>
  
![Untitled Diagram drawio (3)](https://github.com/bashar-27/Lab11/assets/83985765/f67b9f33-599a-47b9-abc5-78b1bb93135d)

<hr>
<p><b>The Hotel</b> table is connected to the HotelRoom table via a one-to-many relationship based on the HotelId foreign key.

  <b>The RoomLayout</b> table is connected to the HotelRoom table via a one-to-many relationship based on the RoomLayoutId foreign key.

<b>The Amenity</b> table is not directly connected to any other table, as it represents a separate entity.

<b>The HotelRoom</b> table serves as a join table connecting the Hotel and RoomLayout tables. It also has a one-to-many relationship with the RoomAmenity table based on the HotelRoomId foreign key.
 
 <b>The RoomAmenity</b> table represents the many-to-many relationship between HotelRoom and Amenity using the HotelRoomId and AmenityId foreign keys.
</p>

