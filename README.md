```
namespace TasosKyr;

class About extends Me
{

    public function getBasicInfo(): array
    {
        return [
            'name' => [
                'first' => 'Anastasios' || 'Tasos',
                'last' => 'Kyrtsis',
            ],
            'based_in' => [
                'city' => 'Berlin',
                'country' => 'Germany'
            ],
        ];
    }
    
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Heyflow',
                'position' => 'Software Engineer',
                'specialty' => 'Full-Stack'
            ]
        ];
    }

    public function getFavouriteTechnologies(): array
    {
        return [
            Javascript::class,
            Typescript::class,
            NodeJS::class,
            Reactjs::class,
            Vuejs::class,
            Nextjs::class,
            Postgresql::class,
            NestJS::class
            GraphQL::class,
            Redis::class,
            AWS::class,
        ];
    }

}
```
