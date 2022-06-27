using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace FinalExamQ2c
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Paint(object sender, PaintEventArgs e)
        {

        }
        protected override void OnPaint(PaintEventArgs paintEvent)
        {
            Graphics g = paintEvent.Graphics;
            SolidBrush brush = new SolidBrush(Color.RoyalBlue);
            Pen pen = new Pen(Color.Black);

            Size size = this.ClientSize;
            int width = size.Width;
            int height = size.Height;

            //int width = this.Width;
            //int height = this.Height;

            int recWidth = (width / 2);
            int recHeight = (height / 2);
            double y = (height * 0.25);//if the form were a square of 100 units x would be 25
            double x = (width * 0.25);//same for y

            int newY = Convert.ToInt32(y);
            int newX = Convert.ToInt32(x);

            g.FillRectangle(brush, newX, newY, recWidth, recHeight);
        }

        private void Form1_Resize(object sender, EventArgs e)
        {
            Invalidate();
        }
    }
}
