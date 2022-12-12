<!-- import React from 'react'
import { Line } from "react-chartjs-2"
import { Chart as chartjs, CategoryScale, LinearScale, PointElement, LineElement, Title, Tooltip, Legend } from "chart.js"

chartjs.register(CategoryScale, LinearScale, PointElement, LineElement, Title, Tooltip, Legend)

const Chart = ({ arr = [], currency, days }) => {
    const prices=[1,2,3,45];
    const date=["12/22/2","12/453/23","756/3/4"];

    const data={}


    return (

        <Line options={{
            responsive: true,
        }}
            data={{
                labels:date,
                datasets:[{
                    label:`Price in ${currency}`,
                    data: prices,borderColor:"rgb(255,99,132)",
                    backgroundColor:"rgba(255,99,132,0.5)"

                }]
            }}
        />
    )
}

export default Chart -->