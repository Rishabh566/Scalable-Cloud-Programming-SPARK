# Scalable-Cloud-Programming-SPARK

Step 1: Open Your terminal and navigate to project root directory (SCP_Project-x21171203). You should change to this directory before starting PySpark.

>> cd ~/SCP_Project-x21171203

Step 2: Start 'PySpark' server and open Jupyter notebook on browser from the 'URL:port' that will be printed as a output by executing below command.

>> pyspark

Step 3: When Jupyter notebook starts you will be able to see 5 .ipynb file that are as mentioned below. Click on any of the below mentioned file to open it in new tab.

Question_2.ipynb
Question_6.ipynb
Question_12.ipynb
Question_16.ipynb
Question_17.ipynb

Step 4: Click on 'cell' in menu bar and select 'Run All' option and this will Run all the cells in that .ipynb file to give the analysis results and graphs.


--- D0 'step 3' and 'step 4' to run all the the questions ---


<mxfile host="Electron" modified="2023-08-11T15:53:38.816Z" agent="Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) draw.io/21.6.5 Chrome/114.0.5735.243 Electron/25.3.1 Safari/537.36" etag="POt_hBExn-fjG-U1H0Bi" version="21.6.5" type="device">
  <diagram name="Page-1" id="jq66sD4FYwAVN5NTGfNe">
    <mxGraphModel dx="1026" dy="686" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="UXHISGUNJXsAoavJjUe2-2" value="" style="swimlane;startSize=0;" vertex="1" parent="1">
          <mxGeometry x="526" y="274" width="130" height="55" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-33" value="Cluster Manager" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-2">
          <mxGeometry x="18" y="12.5" width="110" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-46" value="2" style="ellipse;whiteSpace=wrap;html=1;aspect=fixed;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-2">
          <mxGeometry x="6" y="18.5" width="20" height="20" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-13" value="" style="swimlane;startSize=0;" vertex="1" parent="1">
          <mxGeometry x="700" y="306" width="190" height="140" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-14" value="" style="swimlane;startSize=0;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-13">
          <mxGeometry x="15" y="60" width="160" height="70" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-15" value="" style="swimlane;startSize=0;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-14">
          <mxGeometry x="7" y="22" width="70" height="40" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-19" value="Task" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-15">
          <mxGeometry x="10" y="5" width="50" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-16" value="" style="swimlane;startSize=0;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-14">
          <mxGeometry x="84" y="22" width="70" height="40" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-20" value="Task" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-16">
          <mxGeometry x="10" y="5" width="50" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-18" value="Executor" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-14">
          <mxGeometry x="45" y="-4" width="70" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-17" value="" style="swimlane;startSize=0;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-13">
          <mxGeometry x="15" y="30" width="160" height="24" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-21" value="Cache" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-17">
          <mxGeometry x="50" y="-3" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-22" value="Worker" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-13">
          <mxGeometry x="65" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-23" value="" style="swimlane;startSize=0;" vertex="1" parent="1">
          <mxGeometry x="700" y="157" width="190" height="140" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-24" value="" style="swimlane;startSize=0;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-23">
          <mxGeometry x="15" y="60" width="160" height="70" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-25" value="" style="swimlane;startSize=0;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-24">
          <mxGeometry x="7" y="22" width="70" height="40" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-26" value="Task" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-25">
          <mxGeometry x="10" y="5" width="50" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-27" value="" style="swimlane;startSize=0;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-24">
          <mxGeometry x="84" y="22" width="70" height="40" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-28" value="Task" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-27">
          <mxGeometry x="10" y="5" width="50" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-29" value="Executor" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-24">
          <mxGeometry x="45" y="-4" width="70" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-30" value="" style="swimlane;startSize=0;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-23">
          <mxGeometry x="15" y="30" width="160" height="24" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-31" value="Cache" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-30">
          <mxGeometry x="50" y="-3" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-32" value="Worker" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-23">
          <mxGeometry x="65" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-39" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="UXHISGUNJXsAoavJjUe2-37" target="UXHISGUNJXsAoavJjUe2-2">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="510" y="260" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-37" value="" style="swimlane;startSize=0;" vertex="1" parent="1">
          <mxGeometry x="380" y="274" width="106" height="55" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-38" value="Driver" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-37">
          <mxGeometry x="23" y="12.5" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-45" value="1" style="ellipse;whiteSpace=wrap;html=1;aspect=fixed;" vertex="1" parent="UXHISGUNJXsAoavJjUe2-37">
          <mxGeometry x="14" y="17.5" width="20" height="20" as="geometry" />
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-40" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="UXHISGUNJXsAoavJjUe2-2" target="UXHISGUNJXsAoavJjUe2-23">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="660" y="302" as="sourcePoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-42" value="" style="endArrow=classic;html=1;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" target="UXHISGUNJXsAoavJjUe2-13">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="654" y="301.5" as="sourcePoint" />
            <mxPoint x="660" y="400" as="targetPoint" />
            <Array as="points">
              <mxPoint x="660" y="400" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="UXHISGUNJXsAoavJjUe2-43" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="1" source="UXHISGUNJXsAoavJjUe2-37" target="UXHISGUNJXsAoavJjUe2-13">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="516" y="302" as="sourcePoint" />
            <Array as="points">
              <mxPoint x="516" y="302" />
              <mxPoint x="516" y="220" />
              <mxPoint x="660" y="220" />
              <mxPoint x="660" y="158" />
            </Array>
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>

