# responsive-grid-layout

// grid that spreads over 4 equaly sized box with a specified gap
.wrapper{
    display: grid; 
    gap: 20px; 
    grid-template-columns: repeat(4, 1fr); 
}

// span over 2 grid columns
.grid-col-span-2 { 
    grid-column: span 2; 
} 

// span over 2 grid rows
.grid-row-span-2 { 
    grid-row: span 2; 
}
