using System;
using System.Windows.Forms;

namespace WindowsFormsApp8
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            int a = Convert.ToInt32(textBox1.Text) + Convert.ToInt32(textBox2.Text) +
            Convert.ToInt32(textBox3.Text) + Convert.ToInt32(textBox4.Text) + 
            Convert.ToInt32(textBox5.Text) + Convert.ToInt32(textBox6.Text);
            textBox7.Text = a.ToString();
        }
    }
}
