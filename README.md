# KeyboardControl
A technique to control keyboard inputs


```C#
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace testingKeyboard
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void textBox1_KeyDown(object sender, KeyEventArgs e)
        {
            if (e.KeyCode == Keys.Right)
            {
                MessageBox.Show(" right arrow");
            }
            if(e.KeyCode == Keys.Left)
            {
                MessageBox.Show(" left arrow");
            }
            if (e.KeyCode == Keys.Up)
            {
                MessageBox.Show(" up arrow");
            }
            if (e.KeyCode == Keys.Down)
            {
                MessageBox.Show(" down arrow");
            }
        }
    }
}

```
