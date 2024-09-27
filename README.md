# Movie-Booking-App
- ER Diagram
- Microservice diagram
- UI diagram

try {
    const multiplexId = 1; 
    const response = await axios.get(`http://localhost:8081/multiplex/getMultiplex/${multiplexId}`);
    const multiplexData = response.data;
    console.log(multiplexData);

} catch (error) {
    console.error('Error fetching multiplex data:', error);
}
