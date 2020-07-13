# Hello-World
My Firsy Repository.

......

#include vertex vert
#include fragment frag

struct vert a2v
{
    float4 pos : POSITION;
    float3 normal : NORMAL;
}

struct frag v2f
{
    float4 pos : SV_POSITION;
    float3 worldNormal : TEXCOORD0;
}

v2f vert(a2v v)
{
    v2f v;
    ......
}

fixed4 frag(v2f v) : SV_Target
{
    return fixed4(1,1,1,1);
}

......
