# Movie-Booking-App
- ER Diagram
- Microservice diagram
- UI diagram

try {
    // Pass the path variable directly in the template literal
    const multiplexId = 1; // Example dynamic value for multiplexId
    const response = await axios.get(`http://localhost:8081/multiplex/getMultiplex/${multiplexId}`);
    
    // Store the response data in a constant
    const multiplexData = response.data;

    console.log(multiplexData); // You can now use multiplexData

} catch (error) {
    console.error('Error fetching multiplex data:', error);
}
